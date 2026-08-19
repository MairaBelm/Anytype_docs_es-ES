---
title: "Ajustes del canal"
---

Los ajustes del canal contienen todas las configuraciones de un [canal](/es/basics/channels/): su nombre e icono, quién tiene acceso, cómo se comportan las notificaciones, qué ven los miembros cuando entran y otros detalles. Hay dos formas de abrir los ajustes del canal:

1. Haz clic en el nombre del canal, en la parte superior de la barra lateral.
2. Haz clic derecho en el icono de canal en la barra lateral del arca.

![docs channel settings intro](/assets/docs-channel-settings-intro.jpg)

## Preferencias

La sección **General** está dedicada a la identidad y el comportamiento básico de tu canal.

![docs channel settings general](/assets/docs-channel-settings-general.jpg)

#### Nombre e icono del canal

El nombre y el icono de tu canal serán lo que verán todos los miembros en sus respectivas arcas.

* **Icono**: se genera automáticamente cuando se crea el canal. Para cambiarlo, haz clic en el icono y podrás elegir uno de la biblioteca o cargar una imagen.
* **Nombre**: pasa el puntero sobre el área del icono, haz clic en **Editar** en la parte superior derecha, escribe el nombre nuevo y haz clic en **Guardar**.

#### Página de inicio

La página de inicio es lo primero que aparece cuando tú o cualquier miembro abrís el canal; además, se añade un widget **Inicio** a tu barra lateral.

Puede ser cualquier objeto: elige el que quieras que vean primero los miembros cuando entren al canal.

* **En canales centrados en la conversación**, elige un objeto de chat como página de inicio para que los miembros lleguen directamente a la conversación en directo.
* **En canales de documentación, wikis o conocimiento**, elige un objeto de página, como una página de bienvenida o de resumen que tenga enlaces al resto.
* **En canales de proyecto con una mezcla de contenido**, elige una colección que reúna todo lo que se debe atender.
* **Déjalo vacío** y verás el último objeto abierto cuando vuelvas a entrar en el canal.

#### Vista de barra lateral

Cambia la presentación por defecto de los elementos de la barra lateral: como widgets o como enlaces. Puedes ver más detalles aquí.

#### Tipo de objeto por defecto

Define el tipo de objeto que se usa cuando creas un objeto sin especificar su tipo (por ejemplo, al pulsar Cmd/Ctrl + N o hacer clic en **+** en la barra lateral sin elegir el tipo).

## Miembros

Gestiona el acceso de otras personas al canal. Los usuarios de un espacio compartido se denominan miembros del espacio, y su nivel de acceso depende de su función. Encontrarás más información sobre los espacios compartidos en [Colaboración](/es/collaborate/collaboration/).

![docs channel settings members](/assets/docs-channel-settings-members.jpg)

### Funciones

Los miembros de un espacio pueden tener distintas funciones, cada una con distintos permisos. Comprueba con regularidad la sección de miembros para asegurarte de que todo el mundo tiene los permisos correctos. Encontrarás más detalles en [Funciones de los miembros](/es/collaborate/collaboration/#funciones-de-los-miembros).

<table><thead><tr><th width="167.1015625">Función</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visitante</strong></td><td>Puede ver todo el contenido del espacio. No puede editar objetos, ni participar en chats o debates, ni eliminar nada.</td></tr><tr><td><strong>Editor</strong></td><td>Tiene todos los permisos del visitante. Además, puede editar contenido del espacio y eliminar elementos de forma definitiva.</td></tr><tr><td><strong>Administrador</strong></td><td>Tiene todos los permisos del editor. Además, puede gestionar editores y visitantes.</td></tr><tr><td><strong>Propietario</strong></td><td>Tiene todos los permisos del administrador. Además, puede crear administradores, generar enlaces de invitación y transferir la propiedad del canal.</td></tr></tbody></table>

### Acceso e invitaciones

En esta sección podrás invitar a tu espacio a otras personas y definir sus permisos. Para entender cómo funciona, consulta [Colaboración](/es/collaborate/collaboration/).

* Copiar enlace: una URL para enviar a quien quieras invitar al espacio.
* Código QR: un código QR apto para compartir en lugares públicos.
* Gestionar enlace: ajustes para restringir y controlar los enlaces de invitación.
* Todos: todas las personas que tienen acceso y su función correspondiente.
* Solicitudes: solicitudes de acceso al espacio pendientes de aprobación.
* Editores: muestra solo los miembros que son editores.
* Visitantes: muestra solo los miembros que son visitantes.

## Notificaciones

Define el modo de notificación por defecto para los mensajes en este canal:

* **Activar**: cada mensaje nuevo genera una notificación.
* **Solo menciones**: solo se generan notificaciones cuando te mencionan con @.
* **Deshabilitado**: sin notificaciones (el contador de mensajes sin leer se actualiza, pero en silencio).

Este es un ajuste por defecto que se puede cambiar en cada chat y cada debate de objeto.

![docs channel settings notifications](/assets/docs-channel-settings-notifications.jpg)

## Almacenamiento remoto

La sección «Almacenamiento remoto» muestra el almacenamiento que usa ese canal y el almacenamiento disponible según tu plan de suscripción. Los archivos que se enumeran aquí son los específicos del canal, no los de toda tu arca.

![docs channel settings storage](/assets/docs-channel-settings-storage.jpg)

***

## Modelo de contenido

La sección «Modelo de contenido» es el punto central desde el que gestionar los tipos y propiedades de tu canal.

#### Tipos

Lista de todos los tipos de objeto disponibles en el canal. Aquí puedes hacer lo siguiente:

* Crear tipos nuevos.
* Modificar los tipos existentes: cambiar su nombre, icono, diseño, propiedades por defecto, plantillas...
* Configurar el comportamiento por defecto de cada tipo.

Puedes ver todos los detalles en [Tipos](/es/organize/types/).

![docs channel settings types](/assets/docs-channel-settings-types.jpg)

#### Propiedades

Lista de todas las propiedades definidas en el canal. Aquí puedes hacer lo siguiente:

* Crear propiedades nuevas.
* Modificar sus opciones y añadir otras.
* Ver los tipos que usan cada propiedad.

Puedes ver todos los detalles en [Propiedades](/es/organize/properties/).

![docs channel settings properties](/assets/docs-channel-settings-properties.jpg)

***

## Importar y exportar

La sección «Integraciones» está dedicada a todo lo relacionado con la entrada y salida de datos del canal:

* **Importar**: puedes importar datos desde Notion, Evernote, Obsidian y archivos Markdown / CSV genéricos.
* **Exportar**: puedes hacer una copia de respaldo del canal completo en formato Markdown o Any-Block.

![import](/assets/import.png)

***

## Propiedad de canal

La propiedad del canal se puede transferir a otro miembro; por ejemplo, cuando cambian las responsabilidades del equipo, cuando un miembro se va o cuando se consolidan las funciones.

Sigue estos pasos para transferir la propiedad:

1. Abre la sección «Miembros».
2. Haz clic en **Transferir propiedad** junto al menú de tres puntos de la esquina superior derecha.
3. En la lista de miembros, selecciona el próximo propietario.
4. Confirma tu elección.

Esta será la situación después de la transferencia:

* Ese miembro pasará a ser el nuevo propietario.
* Tú tendrás permisos de editor.
* El nuevo propietario será el único que podrá transferir de nuevo el canal.
* Los límites de suscripción del nuevo propietario se aplicarán a este canal.

![docs channel settings transfer](/assets/docs-channel-settings-transfer.jpg)

## Eliminar canal

El miembro propietario es el único que puede eliminar el canal. Los demás miembros pueden abandonar el canal, con lo que perderán el acceso sin que esto afecte a otros miembros. Sigue estos pasos para eliminar un canal:

1. Ve a la sección General de los ajustes del canal.
2. Haz clic en los tres puntos de la esquina superior derecha.
3. Selecciona «Eliminar canal».
4. Escribe el nombre del canal para confirmar su eliminación.

![docs channel settings delete](/assets/docs-channel-settings-delete.jpg)

:::danger
**La eliminación de un canal es definitiva.** Desaparecerán todos los objetos, chats, debates e historiales para todos los miembros. No se puede deshacer. Si crees que puedes necesitar los datos más adelante, exporta el canal antes de eliminarlo como medida de precaución.
:::
