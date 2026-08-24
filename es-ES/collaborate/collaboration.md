# Colaboración

Anytype te permite colaborar con otras personas sin sacrificar tu privacidad.

A diferencia de las aplicaciones en la nube habituales, en las que tu contenido está en manos de las empresas de alojamiento, Anytype utiliza tecnología local y con cifrado de extremo a extremo. Tu contenido está siempre accesible en tu dispositivo, y solo tienen la clave para desbloquearlo y verlo aquellas personas a las que invites de forma explícita. Los servidores de Anytype pueden hacer una copia de respaldo de tus archivos y sincronizarlos, pero nunca tienen las claves que les permitirían leer tu contenido. Incluso puedes colaborar directamente con otras personas mediante la sincronización entre pares (P2P) o alojarlo en tu propia red.

El resultado: colaboración real, sin que ningún intermediario pueda ver lo que estáis creando.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collaborate.gif" alt=""/><figcaption></figcaption></figure></div>

## Qué significa esto

En Anytype, la colaboración no es un añadido, sino que está ideada desde el principio para ofrecerte soberanía y control sobre tus datos por completo.

* **Privacidad completa:** todo lo que contienen tus espacios compartidos se cifra _antes_ de salir de tu dispositivo. Es imposible que lo lea nadie, aparte de ti y los otros miembros.
* **Sincronización en tiempo real:** los cambios aparecen al instante cuando los miembros están conectados o en la misma red local.
* **Funcionamiento sin conexión:** trabaja libremente sin conexión a Internet. Tus cambios se sincronizarán de forma automática en cuanto establezcas una conexión de red, que puede ser entre pares.
* **Sin la molestia de registrarse:** los colaboradores no tienen que proporcionar su dirección de correo electrónico, pagar una suscripción ni pedir permiso a nadie. Cualquiera puede crear un arca de Anytype al instante.

De esta forma, los espacios compartidos son apropiados en ámbitos confidenciales como equipos de trabajo, periodistas, comunidades de práctica, organización familiar..., cualquier contexto en el que se busque una colaboración sin miradas ajenas.

## Cómo funciona

Con las aplicaciones de nube habituales, tus datos residen en los servidores de la empresa y, a menudo, se permite el acceso de terceros como Apple o Google; por ejemplo, para notificaciones en el teléfono. Anytype hace las cosas de otra manera:

1. **Las claves están en tu dispositivo:** cuando creas un espacio compartido, tu dispositivo genera claves de cifrado únicas. Estas claves no se comparten nunca con Anytype ni con nadie más.
2. **Los datos se cifran antes de salir:** antes de que tus datos y archivos se sincronicen, ya sea con los servidores de Anytype o con el móvil de otra persona, se convierten en un código ilegible.
3. **Envías las claves directamente:** cuando invitas a alguien a un espacio, tu dispositivo le entrega de forma segura y directa la clave de descifrado, sin que Anytype ni nadie más tenga acceso a ella.
4. **Los servidores actúan como mensajeros ciegos:** los servidores de Anytype ayudan a sincronizar y hacer copias de respaldo de tus datos, pero, como no tienen las claves, todo lo que ven es código cifrado.
5. **El descifrado solo se produce en dispositivos de confianza:** los datos codificados solo vuelven a ser contenido legible cuando llegan a los dispositivos de las personas a las que has invitado.

En resumen: tus datos se cifran en tu dispositivo antes de ir a cualquier parte. Solo tenéis las claves tú y los colaboradores a los que invites, lo que significa que ni siquiera Anytype puede ver lo que estáis haciendo.

<div><figure><img src="../../.gitbook/assets/Docs Regular Sync.gif" alt=""/><figcaption><p>Sincronización típica en la nube</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs E2EE Sync.gif" alt=""/><figcaption><p>Sincronización con base local de Anytype</p></figcaption></figure></div>

## Cómo invitar y aceptar invitaciones

1. Haz clic sobre el nombre del canal en la barra lateral para abrir los [ajustes del canal](../settings/channel-settings.md).
2. Haz clic en la sección «Miembros» (o «Invitar a otras personas»).
3. Elige un método de invitación; los métodos disponibles los decide el propietario del espacio.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collaborate Invite.jpg" alt=""/><figcaption></figcaption></figure></div>

### Enlace de invitación

El botón **Añadir miembros por medio de un enlace** genera un enlace que puedes enviar a otras personas para invitarles al espacio, ya sea como enlace de texto o como código QR. Por defecto, todas las solicitudes de incorporación requieren aprobación. Hay varios ajustes importantes que debes tener en cuenta:

* **Activar aprobación automática**: si activas esta opción, quien tenga el enlace accederá al espacio automáticamente sin necesidad de aprobación, algo útil para espacios de tipo comunidad o foro. Es mejor no activarla en espacios privados o confidenciales.
* **Cualquier miembro del canal puede compartir este enlace**: si activas esta opción, todos los miembros del espacio podrán invitar a otros. Esto funciona bien en espacios públicos sin datos confidenciales o espacios privados cuyos miembros son de toda confianza.
* **Restablecer enlace**: si crees que el enlace de invitación existente supone un riesgo, puedes restablecerlo. Esta acción anula de inmediato el enlace y genera uno nuevo, que será el que se use en adelante para obtener acceso al espacio.
* **Aprobar solicitudes**: cuando recibas solicitudes de acceso, apruébalas desde la pestaña «Solicitudes», junto a las pestañas «Todo», «Editores» y «Lectores».

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Invite Link.jpg" alt=""/><figcaption></figcaption></figure></div>

{% hint style="danger" %}
**Procura usar métodos seguros cuando compartas enlaces de invitación con aprobación automática.** Cualquiera que consiga el enlace podrá acceder al espacio sin necesidad de aprobación. Si temes que un enlace de invitación haya caído en malas manos, puedes restablecer el enlace y requerir la aprobación de todas las solicitudes de nuevos miembros.
{% endhint %}

### Añadir miembros

El botón «Añadir miembros» te mostrará una lista de personas a las que puedes invitar a tu espacio. En esta lista aparecen los miembros de otros espacios a los que tú también perteneces. Es una forma cómoda de colaborar con contactos que ya tienes en Anytype sin tener que enviarles un enlace aparte.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collaborate Add.jpg" alt=""/><figcaption></figcaption></figure></div>

{% hint style="info" %}
**Si encuentras muchos desconocidos en esta lista de miembros**, puede deberse a que formas parte de un gran espacio comunitario con muchos miembros que no conoces.
{% endhint %}

### Cómo acceder a canales de otros

Si recibes un enlace de invitación, al hacer clic en él se abrirá Anytype:

1. Si no has iniciado sesión, verás la pantalla para iniciarla o crear un arca.
2. Con la sesión iniciada, aparecerá un mensaje de confirmación que te indicará el canal y la función que tendrás en él.
3. Haz clic en **Aceptar** para acceder. El canal aparecerá en tu arca.

Este proceso es igual con los enlaces con solicitud de acceso; pero en este caso, en lugar de acceder inmediatamente, enviarás una solicitud al propietario, que verá una notificación para aprobarla o rechazarla. Cuando la apruebe, el canal aparecerá en tu arca.

## Miembros

Son miembros del espacio todas las personas que tienen acceso a este. Los miembros pueden referirse otros miembros con menciones `@`, asignarles tareas y participar en conversaciones.

### Funciones

En todos los espacios, los miembros pueden tener distintas funciones con permisos gradualmente más amplios: visitante, editor, administrador y propietario. En resumen:

* Los **visitantes** solo pueden visualizar el contenido.
* Los **editores** pueden crear, modificar y eliminar contenido.
* Los **administradores** pueden gestionar miembros.
* Los **propietarios** pueden hacerlo todo.

<table data-search="false"><thead><tr><th>Permisos</th><th width="102.04296875" align="center">Visitante</th><th width="104.13671875" align="center">Editor</th><th width="108.62109375" align="center">Administrador</th><th width="108.6015625" align="center">Propietario</th></tr></thead><tbody><tr><td>Crear, editar y eliminar objetos</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td></tr><tr><td>Participar en chats y debates</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td></tr><tr><td>Cambiar el nombre y el icono del espacio</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td><td align="center">✓</td></tr><tr><td>Añadir anclados comunes a la barra lateral</td><td align="center">—</td><td align="center">—</td><td align="center">✓</td><td align="center">✓</td></tr><tr><td>Gestionar miembros</td><td align="center">—</td><td align="center">—</td><td align="center">Editores y visitantes</td><td align="center">✓</td></tr><tr><td>Gestionar enlaces de invitación</td><td align="center">—</td><td align="center">—</td><td align="center">—</td><td align="center">✓</td></tr><tr><td>Cambiar el propietario del canal</td><td align="center">—</td><td align="center">—</td><td align="center">—</td><td align="center">✓</td></tr></tbody></table>

{% hint style="info" %}
**Para compartir objetos con fuera de Anytype**, tienes la opción de publicarlos. Al hacerlo, se crea una página web que se puede visitar con el navegador.
{% endhint %}

{% hint style="warning" %}
**No es posible establecer permisos para los objetos por separado.** Todos los miembros de un espacio pueden ver todo su contenido. Si necesitas más separación, trabaja en otro espacio e importa solo el contenido que quieras a compartir con todos.
{% endhint %}

### Cómo gestionar los miembros

En la sección "Miembros", el propietario y el administrador pueden hacer todo esto:

* **Ver la lista** de miembros actuales con sus funciones.
* **Aprobar o rechazar** solicitudes enviadas por personas que quieren ser miembros del espacio.
* **Cambiar la función de los miembros**; por ejemplo, convertir a un visitante en editor.
* **Eliminar miembros**, que recibirán una notificación y perderán el acceso al espacio.
* **Buscar miembros en la lista** con el atajo `Cmd/Ctrl + F`

#### Cambiar el nivel de acceso

* Busca el miembro del espacio
* Haz clic en su función actual.
* Elige la función que desees asignarle o elimina el miembro por completo.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Remove Member.jpg" alt=""/><figcaption></figcaption></figure></div>

#### Límites de puestos de editor

Cada canal tiene un número máximo de editores según el plan de suscripción del propietario. El nivel gratuito admite un número reducido de editores por canal. Los planes de nivel más alto (Builder, Co-Creator, Ultra, suscripciones de grupo) van aumentando este límite. Consulta [Suscripción](../resources/memberships/).

Si se alcanza el límite, solo podrán añadirse miembros como visitantes hasta que el límite aumente o desaparezca un miembro editor, ya sea porque se convierta en visitante o porque se elimine.

## Cómo colaborar con otras personas

#### Trabajar sin conexión y sincronizar

Anytype se ha desarrollado con tecnología de base local, lo que significa que todo funciona sin conexión por defecto y se sincroniza con cifrado de extremo a extremo cuando se establece una conexión de red. No tienes que elegir las páginas que quieres usar sin conexión.

Cuando los miembros están **conectados**, los cambios se actualizan al instante como de costumbre:

* Alguien edita → los demás miembros ven el cambio en tiempo real.
* Se envía un mensaje → aparece en el chat de inmediato.

Cuando los miembros están **desconectados**, todo sigue funcionando:

* Alguien edita → los cambios se guardan en su dispositivo y se ponen en cola para sincronizarlos cuando vuelva a estar conectado.
* Se envía un mensaje → aparece en su dispositivo, pero solo se enviará cuando vuelva a estar conectado.

#### Miembros en chats y debates

El nombre e imagen de perfil de los miembros aparecen junto a sus mensajes y comentarios. Puedes hacer clic en el nombre o la imagen de cualquier miembro para:

* ver su perfil completo (nombre, bio, imagen de perfil),
* conectar en privado (se abre un [canal directo](chats/direct-channels.md).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Direc Channel Connect.jpg" alt=""/><figcaption></figcaption></figure></div>

#### Privacidad en los canales compartidos

Cuando compartes espacios y colaboras con otros en Anytype, tus datos siguen cifrados durante la sincronización; puedes colaborar con total tranquilidad. No obstante, procura compartir espacios solo con personas de confianza, ya que podrán ver y exportar los datos.

Para casos más sensibles y de alta seguridad, usa redes **autoalojadas** para tener el control de los nodos de transmisión. Consulta [Sincronización y respaldo](../data/sync-and-backup/). También puedes usar el modo **solo local** para compartir de forma completamente aislada por medio de una red local.

## Cómo abandonar un canal

Para dejar de ser miembro de un canal, haz esto:

1. En tu arca, haz clic derecho en el canal o abre Ajustes del canal.
2. Haz clic en **Abandonar canal**.
3. Confirma tu elección.

Las contribuciones que hicieras seguirán intactas en el canal después de abandonarlo: Anytype no eliminará tus mensajes de chat ni tus documentos.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Collaborate Leave Channel.jpg" alt=""/><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**Los propietarios de un espacio compartido deben transferir la propiedad a otro miembro antes de abandonarlo.** Si no hay ningún otro miembro, basta con eliminar el canal por completo.
{% endhint %}

## Notas

{% hint style="info" %}
**Usa enlaces de invitación con solicitud de acceso para tener más control.** Los enlaces de invitación con aprobación automática solo deben usarse en espacios que prioricen el acceso rápido y sencillo sobre la protección de datos confidenciales.
{% endhint %}

{% hint style="info" %}
**Haz una copia de respaldo antes de transferir la propiedad.** Exporta el canal (Ajustes del canal > Integraciones > Exportar canal) antes de transferir los derechos de propiedad. Si algo sale mal, al menos tendrás una instantánea.
{% endhint %}

{% hint style="warning" %}
**Por ahora, solo puedes compartir canales completos, no los objetos por separado.** Si quieres compartir públicamente una sola cosa sin controles de acceso, usa la función de [publicación](publish.md).
{% endhint %}

{% hint style="warning" %}
**Una vez eliminado, el canal no se puede recuperar** a menos que alguien lo haya exportado antes. Ten cuidado con la opción «Eliminar canal» en espacios compartidos.
{% endhint %}
