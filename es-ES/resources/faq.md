# Preguntas frecuentes

## General

<details>

<summary>¿Puedo usar dos arcas distintas al mismo tiempo?</summary>

No es recomendable usar dos arcas distintas al mismo tiempo. Lo ideal sería usar un dispositivo distinto (macOS, Windows o Linux) e e iniciar sesión en la otra arca desde allí.

Sin embargo, también hay un truco que funciona solo en el escritorio: crea un acceso directo aparte para tu otra arca y añade el argumento `--user-data-dir="$path"` al comando de inicio (por ejemplo, `--user-data-dir="D:\Anytype"`).

</details>

<details>

<summary>¿Qué hago si no puedo abrir los enlaces de Anytype desde un navegador?</summary>

Puedes abrir cualquier enlace de Anytype si lo pegas en el menú de búsqueda global de Anytype. Atajo: `Cmd/Ctrl + K`

</details>

<details>

<summary>No puedo anclar nada en la barra lateral ni crear widgets.</summary>

La opción «Anclar en el canal» solo está disponible para los propietarios del espacio. Si el espacio no es de tu propiedad y quieres añadir un widget, marca objetos como favoritos con el icono de estrella. Esos favoritos de la barra lateral solo están visibles para ti. Si tus anclados o favoritos no aparecen como widgets, puede que debas cambiar los ajustes del canal. Aquí tienes [más información](../basics/sidebar/widgets.md#opciones-de-los-widgets).

</details>

<details>

<summary>¿Cómo se crean columnas?</summary>

Haz clic en el control que aparece a la izquierda de cada bloque y arrástralos hasta la posición que desees. Aquí tienes [más información](../create/editor/#columnas).

<figure><img src="../../.gitbook/assets/Docs Blocks Columns.gif" alt=""><figcaption></figcaption></figure>

</details>

## Cuenta, seguridad y privacidad

<details>

<summary>He perdido mi clave, ¿qué puedo hacer?</summary>

Anytype no tiene acceso a tu cuenta de ninguna manera, por lo que no tenemos tu clave y no podemos recuperarla. Hay una posibilidad de que puedas recuperarla por tu cuenta. Aquí tienes [más información](../basics/key.md#que-ocurre-si-pierdes-la-clave).

Si no consigues recuperar la clave para acceder a tu arca, Anytype no puede eliminar tu cuenta, ya que no tenemos forma de identificarla ni de relacionarla con tu identidad. Tu arca seguirá cifrada en nuestros nodos de respaldo sin que nadie pueda acceder a ella.

</details>

<details>

<summary>¿Cómo recupero mi clave desde el almacén de claves del sistema operativo?</summary>

**Mac**

Si tu dispositivo es un Mac, Anytype guarda tu clave por defecto en la aplicación nativa Acceso a Llaveros. Es el único lugar en el que la guarda. Si además tienes una copia de respaldo de tus contraseñas en iCloud, es algo que depende de tu configuración. Puedes ver más información sobre la copia de contraseñas en iCloud en la [página de soporte técnico de Apple](https://support.apple.com/es-es/HT204085).

Hemos ideado este sistema como red de seguridad para personas que podrían perder su clave. Estamos barajando otras opciones para el futuro, pero así es como funciona por el momento.

Si has iniciado sesión con tu clave en un Mac, podrás encontrar tu clave aquí:

1. Haz clic y abre el Finder desde el Dock.
2. Haz clic en Aplicaciones y abre Utilidades.
3. Abre la aplicación Acceso a Llaveros.
4. En la barra lateral, selecciona «Llaveros por omisión» e inicia sesión.
5. Busca el ítem de Anytype en la lista y ábrelo.
6. Marca la casilla «Mostrar contraseña» para ver tu clave

**Windows**

Tu clave se almacena en el [Administrador de credenciales](https://support.microsoft.com/es-ES/windows/accessing-credential-manager-1b5c916a-6a16-889f-8581-fc16e8165ac0). Si el Administrador de credenciales no te permite leer una contraseña (falta el botón «Mostrar»), puedes usar [este script de PowerShell](https://gist.github.com/requilence/de8da32adc44d4786559789debb3bf88). Guárdalo en tu ordenador, haz clic derecho sobre él en el explorador de archivos y selecciona «Ejecutar con PowerShell».

**Linux**

Puedes usar [seahorse](https://wiki.gnome.org/Apps/Seahorse/) para buscar tu clave si estás usando [GNOME Keyring](https://wiki.gnome.org/action/show/Projects/GnomeKeyring?action=show\&redirect=GnomeKeyring).

</details>

<details>

<summary>¿Qué estándar seguís para crear la clave de mi arca?</summary>

Usamos el estándar [**BIP39**](https://medium.com/coinmonks/mnemonic-generation-bip39-simply-explained-e9ac18db9477) para generar una frase mnemónica, que luego se utiliza para generar la clave privada de tu arca.

</details>

<details>

<summary>¿Por qué dice Anytype que mi clave es demasiado corta?</summary>

Este problema suele resolverse añadiendo un espacio al final después de pegar la clave.

</details>

<details>

<summary>¿Qué puedo hacer si se me pide introducir la clave / frase de recuperación cada vez que abro Anytype en Linux?</summary>

Es posible que a los usuarios de Linux se les pida su clave cada vez que inicien sesión. Para resolver este problema, instala un llavero. El más popular es [GNOME Keyring](https://wiki.gnome.org/action/show/Projects/GnomeKeyring?action=show\&redirect=GnomeKeyring). Antes, asegúrate de que tener instaladas todas las [dependencias](https://github.com/anyproto/anytype-ts#dependencies).

</details>

## Sincronización y almacenamiento

<details>

<summary>¿Qué ocurrirá si alcanzo mi límite de almacenamiento?</summary>

Puedes seguir usando la aplicación sin interrupciones; los objetos que crees y modifiques se seguirán sincronizando con normalidad. La diferencia es que los archivos, imágenes, vídeos, etc. dejarán de sincronizarse hasta que vuelvas a estar por debajo del límite o adquieras un plan para aumentarlo.

La aplicación de Anytype intentará sincronizar archivos de vez en cuando para comprobar tu límite, pero esto no debería ocupar recursos en tu dispositivo.

</details>

<details>

<summary>¿Hay alguna solicitud de red cuando se usa el modo solo local?</summary>

Podemos garantizar que no habrá solicitudes a nuestra red de Anytype, pero nuestra telemetría seguirá enviando solicitudes (podrás desactivarlo más adelante). Además, el cliente sigue teniendo que enviar solicitudes para que algunas características (bloques incrustados, marcadores, etc.) funcionen correctamente.

</details>

<details>

<summary>¿Los invitados de mi canal pueden usar Anytype en modo solo local?</summary>

Cuando no estén en la misma red local, estos invitados tendrán que conectarse a la red de Anytype para ver todos los cambios del canal.

</details>

## Varios

<details>

<summary>Por qué no existe una versión de Anytype en el navegador?</summary>

No existe una versión de la aplicación para navegador. Anytype es una aplicación independiente que funciona en dispositivos de escritorio o móviles. Las aplicaciones de navegador tienen muchos puntos de vulnerabilidad que pondrían en riesgo nuestro compromiso con la seguridad y el cifrado de los datos. 

</details>

<details>

<summary>¿Qué características no están disponibles aún en la versión móvil?</summary>

* Columnas
* LaTeX insertado
* [Consultas insertadas](../advanced/feature-list-by-platform/inline-queries.md "mention")
* Vistas de kanban, calendario y gráfico
* [Fórmulas](../advanced/feature-list-by-platform/formulas.md "mention")
* [Incrustados](../advanced/feature-list-by-platform/embeds.md "mention")
* [CSS personalizado](../advanced/feature-list-by-platform/custom-css.md "mention")
* [](/broken/pages/jSr1UnNvM2cdphyK8ywU "mention")
* [Gráfico](../advanced/feature-list-by-platform/graph.md "mention") y flujo
* [Importar y exportar](../data/import-and-export/ "mention")
* Código PIN

</details>

<details>

<summary>¿Por qué no puedo buscar dentro de los objetos en iOS?</summary>

Actualmente, esta función no está disponible en iOS.

</details>

<details>

<summary>¿Por qué no puedo buscar ni seleccionar objetos en lote dentro de las consultas en el móvil?</summary>

Actualmente, estas funciones no están disponibles en iOS ni en Android.

</details>

<details>

<summary>¿Tiene Anytype un programa de recompensas por notificar fallos?</summary>

Como organización sin ánimo de lucro que aún no ha alcanzado unos ingresos sostenibles, no disponemos de ningún programa de recompensas por notificar fallos. Si puedes demostrar que has encontrado una vulnerabilidad crítica en nuestras aplicaciones pero no quieres divulgarla, podemos hablar de una posible recompensa. Consulta esta [página](https://github.com/anyproto/.github/blob/main/docs/SECURITY.md) de nuestro GitHub para obtener más información.

</details>

<details>

<summary>¿Cuáles son los requisitos mínimos?</summary>

* En las versiones de escritorio, Electron sigue a Chrome, que a su vez sigue las [directrices de soporte del proveedor](https://support.google.com/chrome/a/answer/7100626?hl=es).
  En este momento, son las siguientes:
  * Windows 10 o superior.
  * macOS 12 Monterey o superior.
  * Ubuntu 18.04, Debian 10, openSUSE 15.5 o Fedora Linux 38 o superiores de 64 bits.
* En Android (si se instala desde Google Play), el mínimo es Android 8.0 y un dispositivo de 64 bits con 4 GB de RAM.
* En iOS, es iOS 17.

</details>

<details>

<summary>¿Dónde está instalado Anytype?</summary>

* En Windows 10 o superior, suele ser\
  `C:\Users\<username>\Appdata\Local\Programs\anytype`\
  **\<username\>** es el nombre de tu usuario, es decir, tu directorio de trabajo.
* En MacOS, es\
  `HDD > Users >`_`Usuario`_`> Library > Application Support > anytype `
* En Linux, el directorio de trabajo está en `~/.config/anytype`
* En Android es la ubicación por defecto, normalmente _device/data/app_​.
  También guardamos algunas cachés en _device/data/data/io.anytype.app_
  El directorio de Anytype se guarda en una carpeta de datos de aplicación protegida a la que no puede acceder el usuario del dispositivo Android.
* En iOS es la ruta de instalación normal, determinada por iOS.

</details>

<details>

<summary>¿Puedo instalar Anytype en un Chromebook?</summary>

Hay varias formas de instalar Anytype en un Chromebook, pero lo más sencillo sería usar una [AppImage](https://download.anytype.io). Para ver la guía completa de uno de los miembros de nuestra comunidad, haz clic [aquí](https://community.anytype.io/t/guide-to-use-anytype-on-a-chromebook/12181).

</details>

## Notas

Las arcas creadas antes de la versión 0.44.0 tienen un espacio inicial. Puedes eliminar este canal si ya no lo necesitas o migrar tus datos a un canal diferente usando la función de [importación y exportación](../data/import-and-export/ "mention").
