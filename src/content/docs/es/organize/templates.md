---
title: "Plantillas"
description: Modelos preconfigurados para objetos nuevos
---


Una **plantilla** es un diseño de página que puedes reutilizar. En lugar de empezar con cada nota, tarea o proyecto desde una página en blanco, defines un buen punto de partida que se convertirá en la base de cada objeto que crees a partir de ese momento.

![docs template introduction](/assets/docs-template-introduction.jpg)

## Qué significa esto

Las plantillas tienen tres ventajas:

* **Normalizan tus objetos**: así tendrán todos el mismo formato.
* **Te ahorran tiempo**: configuras la plantilla una vez y la reutilizas automáticamente.
* **Reducen los errores**: no tienes que introducir a mano los mismos datos una y otra vez.

## Cuándo usar plantillas

El mejor uso de las plantillas es con objetos en los que te encuentres introduciendo el mismo contenido con una estructura similar cada vez que los creas, como recetas de cocina, reseñas de libros, paneles de proyectos y despliegues de contenido.

Por otra parte, es mejor no incluir demasiado en una plantilla si puede suponerte mucho trabajo de actualización en el futuro. Céntrate en incluir solo lo más importante en cada plantilla.

## Cómo funciona

* Cada objeto nuevo que crees usará por defecto la plantilla que hayas establecido.
* Las plantillas solo se aplican a los objetos en el momento en que los creas. Si las modificas después, esos cambios no se aplicarán a los objetos que hayas creado con la versión anterior.
* Puedes tener varias plantillas para cada [tipo](/es/organize/types/), pero solo puedes elegir una como plantilla por defecto.
* Puedes elegir una plantilla distinta en el momento de crear el objeto, pero no tendrás esa opción después de haberlo creado.
* También puedes elegir la plantilla por defecto para objetos creados desde [consultas](/es/organize/queries/) y [colecciones](/es/organize/collections/).
* También puedes elegir la plantilla por defecto para objetos creados desde [vistas](/es/organize/views/).

Estos son todos los elementos que puedes configurar con una plantilla:

<table data-search="false"><thead><tr><th width="181.5">Elemento</th><th>Modo de uso</th></tr></thead><tbody><tr><td><strong>Título</strong></td><td>«Rellenar nombre» dará el mismo título a todos los objetos creados con esta plantilla. «Nombre vacío» no les pondrá ningún título.</td></tr><tr><td><strong>Icono</strong></td><td>Puedes elegir un emoticono o subir una imagen.</td></tr><tr><td><strong>Portada</strong></td><td>Puedes elegir cualquier imagen de la galería o subir una.</td></tr><tr><td><strong>Descripción</strong></td><td>Muestra u oculta la descripción con un texto (o sin texto).</td></tr><tr><td><strong>Ancho</strong></td><td>Establece el ancho de la página, Esto también se puede configurar en el diseño del tipo.</td></tr><tr><td><strong>Propiedades</strong></td><td>Puedes establecer valores por defecto para las propiedades.</td></tr><tr><td><strong>Bloques</strong></td><td>Puedes añadir bloques y diseños de maquetación a la página.</td></tr></tbody></table>

## Cómo crear una plantilla

Las plantillas se crean exactamente del mismo modo que un objeto. Añade bloques de contenido, rellena las propiedades y dale un nombre. Mientras editas la plantilla, los cambios se guardan automáticamente.

![docs templates setting up](/assets/docs-templates-setting-up.gif)

#### A partir de un objeto existente

1. Abre el objeto que quieras usar como plantilla.
2. Haz clic en el botón de tres puntos de la esquina superior derecha.
3. Haz clic en **Usar como plantilla**.

#### Desde un tipo, consulta o colección

1. Abre el tipo, consulta o colección para el que quieras crear una plantilla.
2. Haz clic en el botón «Plantillas» de la derecha.
3. Haz clic en «**+**» para crear una plantilla nueva.

Si configuras aquí una plantilla por defecto, esa plantilla se aplicará a todos los objetos que se creen de este tipo, consulta o colección.

#### Desde los ajustes del canal

1. Abre **Ajustes del canal > Modelo de contenido > Tipos de objeto**.
2. Haz clic en el tipo al que quieres añadir una plantilla.
3. Busca la sección **Plantillas** en el panel derecho.
4. Haz clic en «**+**» para crear una plantilla nueva.

#### Modificar una plantilla existente

1. Pasa el puntero sobre una plantilla.
2. Haz clic en el botón de tres puntos que aparece.
3. Selecciona **Editar plantilla** en el menú.

:::caution
**Los cambios de la plantilla solo se aplicarán a los objetos que crees con ella a partir de ese momento**. Los objetos que hayas creado con versiones anteriores de esa plantilla no reflejarán estos cambios, ya que las plantillas solo se aplican cuando se crea el objeto.
:::

## Cómo usar las plantillas

#### Crear objetos con plantillas

1. Crea un objeto con tu [método habitual](/es/create/objects/#cómo-crear-objetos).
2. Se le aplicará automáticamente la plantilla por defecto.
3. Empieza a editar el contenido.

![docs template default](/assets/docs-template-default.jpg)

#### Usar una plantilla distinta

Es posible que tengas varias plantillas. Antes de realizar cualquier cambio en un objeto nuevo, tienes la posibilidad de cambiar la plantilla que se le aplica.

1. Crea un objeto nuevo.
2. Haz clic en el botón **Este tipo tiene X plantillas**.
3. Elige la plantilla que prefieras.

Las plantillas se aplican en el momento de crear un objeto. Por esta razón, en cuanto editas el objeto pierdes la posibilidad de cambiar su plantilla. Si quieres aplicarle una plantilla distinta después de editarlo, puedes abrir la plantilla, copiar su contenido y pegarlo en el objeto.

![docs templates switch](/assets/docs-templates-switch.gif)

#### Cambiar la plantilla por defecto

1. Abre el tipo.
2. Haz clic en el botón «Plantillas» de la derecha.
3. Pasa el puntero por la plantilla que quieras y haz clic en el botón de tres puntos.
4. Selecciona **Establecer por defecto** en el menú.

![docs templates default](/assets/docs-templates-default.jpg)

#### Establecer la plantilla por defecto para una vista

Puedes establecer la plantilla por defecto de cada [vista](/es/organize/views/). De esta forma, un tipo puede tener varias vistas con una plantilla distinta para cada una.

1. Abre un tipo, consulta o colección.
2. Haz clic en la flecha desplegable que hay junto al botón «Nuevo».
3. Elige **Plantilla para esta vista**.

Cuando estés en esta vista y hagas clic en el botón «Nuevo», se aplicará automáticamente la plantilla que has seleccionado. Esta opción tiene precedencia sobre la plantilla por defecto que hayas establecido para todo el tipo, siempre que crees el objeto desde esta vista.

![docs template view](/assets/docs-template-view.jpg)

#### Proteger las plantillas

Si quieres asegurarte de que la plantilla no varíe, puedes protegerla para evitar cambios accidentales. Ten en cuenta que esto no te impide eliminar la plantilla, pero las plantillas eliminadas se pueden restaurar desde la papelera. Para proteger una plantilla, sigue estos pasos:

1. Abre la plantilla.
2. Haz clic en el botón de tres puntos de la esquina superior derecha.
3. Selecciona la opción **Proteger plantilla**.

![docs template lock](/assets/docs-template-lock.jpg)

#### Duplicar plantillas

Para crear una variante de una plantilla existente, sigue estos pasos:

1. Haz clic en «Plantillas».
2. Busca la plantilla que quieres copiar.
3. Haz clic en el menú de tres puntos > **Duplicar**.
4. Edita la copia para crear tu variante.

Esto resulta útil para mejorarlas poco a poco y para crear versiones personalizadas de una misma plantilla.

#### Título aplicado por la plantilla

Las plantillas tienen la opción de aplicar su título como nombre a los objetos. Esta es la forma de controlar esa opción:

1. Abre la plantilla.
2. En el área del título, verás un botón que alterna entre **Rellenar nombre** y **Nombre vacío**.
   1. **Rellenar nombre**: los objetos que crees tendrán el título de la plantilla; puedes escribir uno nuevo.
   2. **Nombre vacío**: los objetos que crees tendrán un título en blanco para que tú lo escribas

Usa **Nombre vacío** cuando el nombre de la plantilla sirva solo para distinguirla (por ejemplo, si «Entrada de diario» es el nombre de la plantilla, pero no quieres que cada entrada empiece con «Entrada de diario» como título).

![docs template title name](/assets/docs-template-title-name.jpg)

## Varias plantillas

Puedes tener muchas plantillas para un mismo tipo. Estas son algunas sugerencias:

* **Tipo Nota**: plantillas para «Entrada de diario», «Nota de reunión», «Nota de lectura», «Captura de ideas».
* **Tipo Tarea**: plantillas para «Informe de fallos», «Solicitud de función», «Mantenimiento periódico».
* **Tipo Documento**: plantillas para «Revisión semanal», «Descripción técnica», «Post mortem», «Presentación rápida»

## Plantillas con propiedades

Para uniformar más tus objetos, las propiedades de las plantillas pueden tener valores preasignados. Por ejemplo:

* **Estado** = «Borrador» por defecto para ideas nuevas de contenido.
* **Prioridad** = «Baja» por defecto para tareas nuevas.
* **Autor** = «Usuario actual» por defecto para las sugerencias.
* **Etiquetas** = etiquetas predefinidas relevantes para la plantilla.

Cuando creas un objeto a partir de esa plantilla, se le aplican estos valores por defecto. Puedes cambiarlos en el objeto si quieres; solo se asignan a las propiedades como punto de partida.

## Cómo eliminar plantillas

1. Abre la lista de plantillas del tipo.
2. Haz clic en el menú de tres puntos de la plantilla y selecciona **Eliminar**.

La plantilla se traslada a la papelera, desde donde puedes restaurarla. **Los objetos que se crearon con esta plantilla no se ven afectados**: conservan el contenido que les proporcionó la plantilla. Simplemente, la plantilla deja de estar disponible para crear más objetos.

## Notas

:::note
**Crea tus objetos y luego crea una plantilla.** Empieza por crear un objeto real con el diseño que quieres, trabaja en él hasta perfeccionarlo y, entonces, guárdalo como plantilla. Es un método más fiable que diseñar una plantilla desde cero de forma abstracta y arriesgarte a que no atienda a tus necesidades reales.
:::

:::note
**Establece una plantilla por defecto para cada vista en los canales compartidos.** Si un canal de equipo tiene una vista «Lista de fallos» y otra «Solicitudes de funciones», le conviene tener plantillas distintas para cada una: el botón Nuevo de «Lista de fallos» usa la plantilla de informe de errores, mientras que el de «Solicitudes de funciones» usa su propia plantilla. Así, los miembros del canal crean el tipo correcto de objeto sin pararse a pensarlo.
:::
