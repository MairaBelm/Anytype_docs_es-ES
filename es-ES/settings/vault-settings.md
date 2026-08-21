# Ajustes del arca

Básicamente, tu [arca](../basics/vault.md) es tu cuenta. Esta sección contiene tus preferencias y configuraciones. Tienes varias formas de acceder a ella: 

1. Abre la [barra lateral del arca](../basics/sidebar/).
2. Haz clic en la imagen de tu perfil, en la esquina inferior izquierda.

O bien usa el menú de tu sistema operativo: 

1. Abre el menú de Anytype en la barra superior de la aplicación (macOS, Windows, Linux).
2. Ve a **Ajustes**.
3. Selecciona la opción **Arca**.

## Perfil

Aquí puedes añadir tu **nombre, tu biografía** y tu **imagen de perfil**. Cuando estás en un espacio, tu perfil también se trata como un objeto llamado «Miembro del espacio».

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/profile-info.png" alt=""/><figcaption></figcaption></figure></div>

## Aplicación

### Preferencias

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/preferences (3).png" alt=""/><figcaption></figcaption></figure></div>

#### Aspecto

* **Modo de color:** elige entre el modo claro, el oscuro o el que use tu sistema.
* **Sonido de notificación:** elige «No» o uno de los tonos disponibles.

#### Interfaz

* **Densidad de la barra de canales: Compacta** (como una franja) o con **Vista previa de mensajes**.
* **Mostrar siempre la barra de pestañas:** si quieres que la barra de pestañas esté siempre visible.
* **Mostrar y ocultar automáticamente la barra lateral** con esta opción desactivada, la barra lateral no se abrirá automáticamente cuando pases el puntero sobre el borde izquierdo de la ventana.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/preferences (4).png" alt=""/><figcaption></figcaption></figure></div>

#### Contenido y vistas

* **Abrir objetos en pantalla completa** los objetos pueden abrirse en pantalla completa o en una ventana modal.
* **Estilo por defecto de enlace a objeto:** los enlaces creados con el comando `/enlace` pueden tener estilo de tarjeta o de texto.
* **Estilo por defecto de bloques de archivo:** los bloques de archivo pueden tener el estilo incrustado o verse como un sencillo enlace.
* **Hacer clic para editar el título en vista de cuadrícula:** un clic en el título de una vista de cuadrícula puede editar el título o abrir el objeto directamente.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/open-grid (1).png" alt=""/><figcaption></figcaption></figure></div>

#### Mensajes

Elige entre enviar los mensajes del chat y los comentarios de los debates con `Entrar` o con `Cmd/Ctrl+Entrar`.

### Idioma y región

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/language.png" alt=""/><figcaption></figcaption></figure></div>

#### Idioma y ortografía

* **Idiomas del corrector ortográfico** Puedes activar el corrector ortográfico para más de 40 idiomas o dejarlo desactivado.
* **Idioma de interfaz** Elige una de las versiones traducidas por la comunidad para cambiar el idioma de la interfaz.

#### Fecha y hora

* **Formato de fecha y hora:** Elige el formato de fecha y hora que se usará en toda tu arca.
* **Usar fechas relativas:** Elige si quieres presentar las fechas de forma relativa (por ejemplo, como «hoy» o «mañana») o prefieres que siempre se use la fecha concreta.
* **La semana empieza el:** Puedes elegir si tu semana empieza el domingo o el lunes. Ve a tus ajustes actualizados para aplicar el cambio en el selector de fechas.

### Código PIN

Configura un código PIN para bloquear la ventana de escritorio de Anytype y añadir más privacidad. Funciona de esta forma: 

* **Bloqueo automático:** la aplicación te pedirá el PIN cuando transcurra el tiempo de inactividad que elijas (1 minuto, 5 minutos, 10 minutos o 1 hora) y cada vez que visualices tu [clave](../basics/key.md) en los ajustes.
* **El PIN es específico del dispositivo:** el bloqueo mediante PIN funciona exclusivamente en el ordenador en el que se crea. Configurarlo, cambiarlo o eliminarlo en un ordenador no afecta a los demás dispositivos.
* **Bloqueo de la aplicación en la pantalla:** el PIN actúa únicamente como un bloqueo visual de la interfaz de la aplicación. No está vinculado a tu cuenta y no funciona como clave secundaria.
* **El PIN no es un cifrado añadido:** tanto si configuras un PIN como si lo pierdes, la protección de tus datos no se altera. Tu arca siempre estará cifrada por medio de tu clave.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Vault Settings Pin.jpg" alt=""/><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**El PIN bloquea la aplicación en un único dispositivo.** No forma parte de tu cuenta y no es una segunda clave: no cifra nada, y configurarlo o perderlo no supone ningún cambio en la protección de tus datos. Tus datos están cifrados con tu [clave](../basics/key.md).
{% endhint %}

#### Si no recuerdas el PIN

Olvidar tu PIN nunca te impedirá acceder a tu arca ni pondrá tus datos en peligro. Para recuperar el acceso a la aplicación, ten a mano tu [clave](../basics/key.md) y sigue estas instrucciones: 

1. En la pantalla de bloqueo, selecciona «He olvidado mi PIN» y confirma.
2. Se cerrará la sesión de Anytype en ese dispositivo y se borrará el PIN.
3. Vuelve a acceder con tu clave. Tus datos locales siguen a salvo en el dispositivo y el requisito del PIN se habrá eliminado.

> Nota para solucionar problemas: Si la opción de restablecer el PIN no aparece en tu pantalla de bloqueo, actualiza Anytype a la versión más reciente. Reinstalar la aplicación no sirve para restablecer el PIN, ya que este se almacena en el sistema operativo, no con los datos de aplicación de Anytype.

#### Más seguridad que la de un PIN

Tu primera línea de defensa debe ser la seguridad del sistema operativo, antes que el PIN de una aplicación. Estas son las prácticas recomendables:

* **Crea cuentas separadas en el sistema operativo:** no compartas nunca tu sesión en el ordenador. Configura perfiles de usuario para impedir que otros accedan a los archivos locales de la aplicación o a los datos de tu sesión.
* **Utiliza contraseñas:** crea una contraseña fuerte para tu cuenta de usuario.
* **Activa el bloqueo automático:** configura tu sistema operativo para que bloquee la pantalla automáticamente tras un periodo breve de inactividad.
* **Bloquea antes de alejarte:** acostúmbrate a bloquear la pantalla manualmente siempre que te alejes del ordenador, sobre todo en lugares públicos. Lo mejor es configurar un atajo para hacerlo. 

***

## Arca y clave

### Clave de acceso

Para conectar tu dispositivo móvil, puedes acceder a tu clave o escanear el código QR. Tienes más detalles en [Clave](../basics/key.md "mention").

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Welcome 3.jpg" alt=""/><figcaption></figcaption></figure></div>

**Eliminación del arca:** Si quieres eliminar tu arca, puedes hacerlo desde esta sección. Tienes más información aquí: [Borrado y recuperación de datos](../data/data-erasure-and-recovery.md "mention")

***

## Gestión de datos

### Almacenamiento local

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/local-storage.png" alt=""/><figcaption></figcaption></figure></div>

* **Archivos locales:** si quieres, puedes transferir a la red de Anytype los archivos que almacenas en Anytype.
* **Acceso sin conexión:** puedes controlar si los datos se sincronizan para usarlos sin conexión con un límite de almacenamiento (No, 20 MB, 100 MB, 250 MB, 1 GB o Ilimitado).
* **Ubicación de datos:** también puedes decidir dónde se almacenan tus datos (solo en ordenador).

### Canales

Aquí encontrarás una lista de todos tus canales, tu nivel de acceso y su estado en la red. El menú de tres puntos también contiene las opciones «Enlace de invitación», código QR y «Eliminar canal».

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/channels-settings.png" alt=""/><figcaption></figcaption></figure></div>

### Mis sitios

Aquí podrás ver y gestionar los objetos que hayas publicado.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image (35).png" alt=""/><figcaption></figcaption></figure></div>

### Claves de API

Aquí puedes ver, gestionar y crear claves de API.
