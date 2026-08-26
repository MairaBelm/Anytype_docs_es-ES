---
description: Conversaciones en tiempo real junto a tu trabajo.
---

# Chats

Un **chat** es un hilo de conversación en tiempo real dentro de un canal. A diferencia de los mensajes de una aplicación aparte, los chats residen junto a tus notas, tareas y documentos. y la conversación es privada, cifrada y ligada al contexto al que hace referencia.

Los chats te ofrecen el ritmo de una aplicación de mensajería (respuestas rápidas, reacciones, archivos enviados), pero con un detalle importante: los mensaje pueden incluir referencias a objetos de Anytype, y también crearlos o abrirlos. Un pensamiento escrito se convierte en una página; una captura de pantalla se convierte en un objeto de archivo; una pregunta se puede responder con el enlace a un objeto que se abre al hacer clic.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chat Launch.jpg" alt=""><figcaption></figcaption></figure></div>

## Cómo funciona

Al igual que los documentos y archivos, los chats son [objetos](../../create/objects/) con su propio [tipo](../../organize/types.md) dedicado. Esto significa que los chats:

* aparecen en la sección Tipos de la barra lateral como «Chats»,
* pueden tener sus propias [propiedades](../../organize/properties.md),
* se pueden organizar mediante [vistas](../../organize/views.md), [consultas](../../organize/queries.md) y [colecciones](../../organize/collections.md),
* se pueden añadir como [widgets](../../basics/sidebar/widgets.md) a la barra lateral,
* se pueden mencionar con `@` o insertar como enlaces en otro objeto.

«Chat» es un tipo del sistema, por lo que no admite plantillas ni cambios de diseño. Por lo demás, un chat se comporta como cualquier otro tipo de objeto.

## Cómo crear chats

#### Un solo chat

1. Haz clic en el desplegable Crear en la cabecera de la barra lateral del canal.
2. En la lista de tipos, selecciona «Chat».
3. Da un nombre al chat.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chat Create.jpg" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Fija un chat como página de inicio** en canales donde la conversación sea lo principal.
{% endhint %}

#### Varios chats

Un solo canal puede contener varios chats. Puedes iniciar conversaciones sobre temas concretos en el mismo lugar en el que trabajas y organizarlas por medio de [vistas](../../organize/views.md).

1. Ve a Chats en la sección Tipos de la barra lateral.
2. Crea un chat nuevo.
3. Añade las propiedades que quieras.
4. Configura filtros y criterios de orden a tu gusto.
5. Elige el diseño que desees.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chats Multiple.jpg" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Usa varios chats en canales grandes.** Un único canal de equipo puede tener varios chats. Silencia los que no te interesen y deja otros con solo menciones.
{% endhint %}

#### Widget de chats

El widget de chats funciona como cualquier otro widget de tu barra lateral:

* lo puedes anclar para que esté siempre visible,
* puedes elegir su aspecto (compacto, lista, etc.).

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chat Widget.jpg" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Agrupa tus chats por categorías y usa un diseño de kanban** para crear una lista organizada en la barra lateral.
{% endhint %}

## Cómo usar el chat

#### Enviar mensajes

El cuadro para enviar mensajes está en la parte inferior de cada chat. Puedes enviar:

* **Texto**, escrito en línea, con formato Markdown completo.
* **Menciones**: escribe `@` para mencionar a un miembro o cualquier objeto.
* **Adjuntos**: arrastra un archivo, pega una imagen o comparte un objeto con el botón «más».

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chats Using.jpg" alt=""><figcaption></figcaption></figure></div>

#### Reacciones

Pasa el puntero sobre un mensaje y haz clic en el icono sonriente para reaccionar con un emoji.

Cuando varias personas reaccionen con el mismo emoji, verás un contador junto a esa reacción. Haz clic en la reacción para añadir o quitar la tuya.

#### Respuestas

Haz clic derecho en un mensaje (o pasa el puntero y haz clic en el icono de respuesta) para responder a ese mensaje concreto. Tu respuesta cita el original en la parte superior: los destinatarios ven el contexto de inmediato y pueden hacer clic en la vista previa citada para **ir al mensaje original**.

Desde ahí, el botón de desplazamiento hacia abajo te lleva primero a la respuesta y luego al final del chat; así puedes navegar por las respuestas sin perder tu lugar.

#### Enlaces inteligentes de Anytype

Cuando pegas un enlace a un objeto de Anytype en el cuadro de mensaje del chat, se convierte automáticamente en una tarjeta. Así, quien recibe el mensaje ve una vista previa del objeto en lugar de una URL larga.

#### Anclar mensajes

Puedes anclar mensajes importantes en el chat:

1. Haz clic derecho en el mensaje.
2. Selecciona **Anclar**.

Los mensajes anclados aparecen en un **recuadro permanente en la parte superior de la conversación**. Si hay varios mensajes anclados, haz clic en el recuadro para pasar de uno a otro, del más reciente al más antiguo.

#### Búsqueda en mensajes de chat

Busca en el chat abierto con **Cmd/Ctrl + F** (o haz clic en el icono de búsqueda de la parte superior del chat). Los resultados aparecen ordenados por fecha en un desplegable con flechas de navegación para desplazarte por ellos de uno en uno.

Para buscar en todos los chats y objetos del canal, usa la búsqueda global (Cmd/Ctrl + K desde cualquier lugar).

#### Editar y eliminar mensajes

Haz clic derecho en un mensaje tuyo (o pasa el puntero y usa el menú de tres puntos) para:

* **Editar**: el mensaje sigue donde está y se marca como editado.
* **Copiar texto**: copia el contenido del mensaje (conserva el formato).
* **Eliminar**: elimina el mensaje por completo.

Solo puedes editar y eliminar tus propios mensajes. Los propietarios de canal no pueden editar los mensajes de otros miembros.

#### Adjuntar archivos

Arrastra un archivo al cuadro de mensaje o pégalo desde el portapapeles. El archivo se carga y ocurre todo esto:

* se convierte en un [objeto de archivo](../../create/files-and-media.md) que puedes encontrar en el canal;
* aparece en el chat como una tarjeta;
* se puede encontrar con la búsqueda global.

Si es una imagen, el mensaje mostrará una miniatura; si es audio o vídeo, mostrará un reproductor.

## Notificaciones de chat

#### Sección No leídos

Cuando algún chat recibe un mensaje nuevo, aparece automáticamente la sección temporal **No leídos** en la barra lateral. Según te pones al día, la sección se reduce hasta que desaparece. Esta sección también muestra notificaciones de los [debates](../discussions.md). Tienes más detalles en la sección [Barra lateral](../../basics/sidebar/sections.md).

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/Docs Chats Unread.jpg" alt=""><figcaption></figcaption></figure></div>

#### Notificaciones de cada chat

Los ajustes de notificación de cada chat te permiten controlar su volumen de notificaciones por separado

1. Abre el chat que desees.
2. Haz clic en los tres puntos de la esquina superior derecha.
3. Selecciona **Notificaciones**.
4. Elige:
   * **Activar** para recibir una notificación con cada mensaje;
   * **Solo menciones** para recibir notificaciones solo cuando te mencionen con `@`;
   * **Deshabilitado** para no recibir ninguna notificación (el contador de mensajes sin leer sí se actualiza).

Estos ajustes son específicos de cada chat y tienen precedencia sobre los ajustes por defecto del canal. Consulta [Notificaciones](../../settings/channel-settings.md#notificaciones) para obtener una imagen completa.

## Ajustes del chat

#### Chat como inicio del canal

Cuando creas un canal, puedes elegir **Chat** como inicio, de modo que lo primero que ve cualquiera que abra el canal es la conversación en directo. Los canales con un chat como inicio son perfectos para:

* reuniones rápidas e intercambios en diferido,
* comunidades y grupos de interés,
* trabajos en los que conversar sea lo principal, con documentos como ingrediente secundario.

Tienes más detalles en [Canales](../../basics/channels.md#tu-pagina-de-inicio).

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/home-chat.png" alt=""><figcaption></figcaption></figure></div>

#### Preferencia para enviar mensajes

Elige cómo prefieres enviar los mensajes en **Ajustes del arca > Aplicación > Mensajes**.

* **Entrar** para enviar (Mayús + Entrar para nueva línea)
* **Cmd / Ctrl + Entrar** para enviar (Entrar para nueva línea)

#### Corrección ortográfica

Los mensajes del chat aplican el corrector ortográfico con el mismo subrayado rojo y sugerencias que el editor. El corrector usa los ajustes de idioma de Anytype, no tienes que configurar nada más. Selecciona los idiomas del corrector ortográfico en **Ajustes del arca > Aplicación > Idioma y región**.

## Canales directos

Para conversar directamente con otra persona, usa los **canales directos**, chats privados de tú a tú sin administradores ni jerarquía. Tienes más detalles en [Canales directos](direct-channels.md).

## Exportar chats

No es posible exportar un chat fuera de su canal. Los mensajes del chat están vinculados a los miembros del espacio, y los datos de cada miembro están protegidos con claves de cifrado únicas. Cuando exportas un espacio y lo importas a otro, ese espacio nuevo se crea con sus propias claves de cifrado y sus miembros.

Por lo tanto, ni los chats como objetos ni los mensajes que contienen se puede exportar; están ligados de forma indisoluble al espacio en el que se crearon.

## Notas

{% hint style="info" %}
**Arrastra objetos al chat para compartir trabajo en desarrollo:** notas, tareas, páginas o incluso otro chat. Los objetos se convierten en tarjetas que los demás pueden abrir con un clic para editarlos de inmediato.
{% endhint %}

{% hint style="info" %}
**Ancla el mensaje de bienvenida.** Cuando alguien se incorpora a un canal con el chat como inicio, lo primero que ve es el mensaje anclado en la parte superior. Úsalo para establecer normas, definir el canal y organizara la participación.
{% endhint %}

{% hint style="info" %}
**Para hablar sobre un objeto determinado, usa su debate en lugar del chat.** Los debates están siempre ligados a su objeto. Los chats sirven para conversar sobre distintos objetos y colaborar en tiempo real. Consulta [debates](../discussions.md).
{% endhint %}
