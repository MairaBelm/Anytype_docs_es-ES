---
hidden: true
---

# Herramienta AnySync Netcheck

Una herramienta sencilla que comprueba la conexión a los nodos de Anytype. Se creó para examinar problemas de red y TLS (sincronización).

La herramienta _Netcheck_ abre una conexión con los nodos coordinadores para establecer comunicación con el protocolo libp2p y las negociaciones handshake de *AnySync*, e intenta ejecutar solicitudes de configuración de red.

***

### Descargar <a href="#p-42130-download-2" id="p-42130-download-2"></a>

Descarga la versión para tu SO desde aquí:

{% embed url="https://github.com/anyproto/any-sync-tools/releases" %}

El archivo .zip contiene todas nuestras herramientas, pero el procedimiento de comprobación de sincronización solo requiere **any-sync-netcheck**.\
(El otro archivo es nuestra [herramienta de autoalojamiento](https://github.com/anyproto/any-sync-tools/blob/main/any-sync-network/README.md).)

### Instalación <a href="#p-42130-installation-3" id="p-42130-installation-3"></a>

**Compilar desde la fuente:**

`go install github.com/anyproto/any-sync-tools/any-sync-netcheck@latest`

***

#### Ejecutar la herramienta <a href="#p-42130-runing-the-tool-5" id="p-42130-runing-the-tool-5"></a>

Ejecuta el archivo llamado

* `any-sync-netcheck`
* _o_ `any-sync-netcheck -v` para obtener una salida detallada.

***

#### Resultado <a href="#p-42130-result-6" id="p-42130-result-6"></a>

*   Si tu sincronización **funciona correctamente**, el registro de salida debería tener un aspecto similar a este:\\

    <figure><img src="../../../.gitbook/assets/Screenshot 2023-08-02 at 16.40.02.png" alt=""><figcaption></figcaption></figure>
* **Si la herramienta detecta algún error**, proporciónanos todos los datos de tu configuración de red, incluyendo VPN, proxy, cortafuegos y antivirus. En este caso, podríamos pedirte que ejecutes un trazado de ruta u otras herramientas del sistema para seguir analizando el problema.
