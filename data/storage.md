# Storage

Anytype is offline first; hence, all data you create will be stored locally first. After that, the data is synced to the backup node and your devices for redundancy. We use a private [IPFS](https://docs.ipfs.tech/concepts/what-is-ipfs/) network to handle storage. It is a Peer-To-Peer file system that facilitates decentralized data storage across devices. Local P2P is supported, meaning that you can sync between your devices directly if they are connected through the same local network. This will work no matter what network mode you use, and it's the only way to sync between your devices if you are using local-only mode.

## How files are handled <a href="#media" id="media"></a>

Media files are not directly downloaded in overall syncing to save bandwidth. Instead, when that file is requested, it is streamed to your device from the backup node or your devices on the network. For example, if you have a 4K Video, it will be streamed from the backup node or P2P devices to your device. So when you open an object with an image, it downloads. When you press play on video & audio, it begins to download. After that, this file will be stored in the application cache.

Furthermore, we use the deduplication feature to reduce storage. For example, if the same picture is uploaded three times, there is only one image copy stored to reduce storage consumption.

You can remove all the media content from your mobile device via the clear cache option in iOS and Android. This will remove all the data altogether and force the app to sync once again entirely. Since the media download works on-premise, you will remove all cached media and clear some storage.

You can also manage your files on desktop by going into `Channel settings -> Manage Channel -> Manage files`.

{% hint style="info" %}
Files are stored inside `flatfs dir` in encrypted fragments, so they can’t be accessed outside of Anytype.
{% endhint %}

## Storage Location

The **Storage Location** is the folder on your hard drive where Anytype keeps your Vault data — every Object, every encrypted block, every file you've uploaded, plus the indexes Anytype uses to make search fast.

By default, Anytype picks a standard location based on your operating system, you can change this to any folder you choose — useful for moving data to a larger drive, an encrypted partition, or a different filesystem.

#### Setting the location at first install

When you first create a Vault, the install screen offers an option to **choose the storage location**. Click the gear icon at the bottom of the welcome screen, browse to the folder you want, and Anytype will create the Vault there.

If you skip this step, Anytype uses the default location. You can always move it later.

#### Changing the location after install

Moving an existing Vault requires logging out, choosing a new location on the login screen, and re-authenticating. Anytype will then redownload your Vault data to the new location from the network. Following these steps:&#x20;

1. Make sure you have your Key. This is critical. Without your 12-word Key you cannot log back in.&#x20;
2. Log out of Anytype. Click your profile icon at the bottom of the Vault Sidebar > Log out.
3. On the login screen, click the gear icon (⚙) in the corner.&#x20;
4. Choose a new folder under Vault Data Location.&#x20;
5. Log back in.&#x20;

Anytype redownloads your Vault from the network to the new location. The time depends on Vault size and your connection speed. After this completes, you're back to your normal Vault — same Channels, same Objects, same data — just stored in a different folder.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/Docs Storage Location.jpg" alt=""><figcaption></figcaption></figure></div>

#### What happens to the old location?

The data in the old folder isn't automatically deleted. Once you've confirmed the new Vault is working correctly:

1. Open the old folder.
2. Verify it contains the old Anytype data files (you'll see encrypted blobs, an `index/` folder, etc.).
3. Delete the folder manually.

This recovers the disk space.

{% hint style="warning" %}
**Do not delete the old folder until you've verified the new location is fully synced.**
{% endhint %}

## Using external drives

To store your Vault on an external drive:

1. **Mount the drive** before logging in. Anytype needs the drive to be available at the path you specify.
2. **Pick the drive's folder** during the storage location selection.
3. **Log in normally.**

This works fine for stationary external drives (a desktop external SSD, a NAS mounted as a local volume). It works less well for drives that connect and disconnect often, since:

* If the drive isn't mounted when Anytype starts, the app can't find your Vault and shows a connection error
* Sync is paused while the drive is unavailable
* Some operations may write to the default location if the external drive disappears mid-operation

For a portable Vault, consider using a fast USB-C SSD that you keep mounted while Anytype is running.

## Using encrypted volumes

You can put your Vault on:

* **macOS FileVault** — works transparently; no special setup
* **Windows BitLocker** — works transparently
* **Linux LUKS / dm-crypt** — works transparently
* **VeraCrypt containers** — supported, but you must mount the container before launching Anytype

Anytype's data is already encrypted at rest (via the Vault's master key derived from your 12-word phrase), so volume-level encryption is an additional layer rather than a substitute. It's useful if you want defense-in-depth or if you're worried about other apps on the device reading filenames or sync metadata.

## Local-only mode

If you choose [Local-only](sync-and-backup/local-only.md) network mode (in Vault Settings > Networks & Backup), your Vault never syncs to any remote server. Your data lives only at the storage location you've chosen, plus any other devices you sync with via local peer-to-peer. Please [see here](sync-and-backup/local-only.md) for more details.

{% hint style="danger" %}
**In Local-only mode, your storage location is the only copy of your data**. Treat the folder like a precious original — back it up regularly, and never let it live somewhere ephemeral (like a temp directory or unmounted drive).
{% endhint %}
