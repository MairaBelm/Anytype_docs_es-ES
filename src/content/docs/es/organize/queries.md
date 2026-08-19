---
title: "Consultas"
description: Presentaciones de los datos de tu base de conocimiento
---


Una consulta es una pregunta que le haces a tu base de conocimiento, contestada al instante y actualizada automáticamente. En lugar de crear a mano una lista de los objetos que buscas, defines unos criterios y la consulta te presenta el resultado en una [vista](/es/organize/views/). Por ejemplo:

* Preséntame todo lo que esté etiquetado como `idea` y se haya creado durante `los últimos 30 días`.
* Preséntame todos los objetos que tengan un estado `activo`, una prioridad `alta` y no estén marcados como `listo`.

![docs queries intro](/assets/docs-queries-intro.jpg)

## Qué significa esto

Los [tipos](/es/organize/types/) y las [propiedades](/es/organize/properties/) dan estructura a tus objetos; las consultas emplean esa estructura para darte respuestas útiles.

* No necesitas recordar dónde has puesto las cosas: el objeto preciso aparece en el momento preciso y en el formato preciso.
* No necesitas ordenarlo todo a mano: defines las reglas una vez y las consultas se actualizan con tu contenido a medida que este crece.

## Cuándo usar consultas

Usa una consulta cuando quieras ver una parte de tu base de conocimiento que cambia constantemente y que sería tedioso mantener a mano. Las consultas se crean y se eliminan sin que esto afecte a los datos de tus espacios. Por ejemplo:

* si quieres una agenda, consulta todo lo que tenga la fecha límite de `hoy`;
* si tienes una revisión periódica, consulta todo lo que tenga el estado `revisar`, ordenado de más antiguo a más nuevo;
* si quieres encontrar un dato, consulta todo lo que tenga la etiqueta `información`.

![docs queries explained](/assets/docs-queries-explained.jpg)

> **Ejemplo:**
>
> Supongamos que tu espacio tiene tres tipos: Libros, Películas y Juegos, con la propiedad «Género» en todos ellos. Si creas una consulta que filtre tus objetos por «Género = Ciencia ficción», el resultado será una vista que presente todos los libros, películas y juegos de ciencia ficción de tu espacio, y estará actualizada siempre con los objetos de esta categoría que vayas creando.
>
> En otras palabras, esta consulta es una respuesta constante a la pregunta _«¿qué material tengo de ciencia ficción?»._ Más abajo tienes un ejemplo de cómo [crear esta consulta](/es/organize/queries/#cómo-crear-una-consulta).

#### Relación entre tipos y consultas

Los [tipos](/es/organize/types/) son, en el fondo, consultas integradas en el sistema. Sin embargo, como cada objeto solo puede tener un tipo, las consultas tienen verdadera utilidad cuando quieres encontrar y agrupar objetos que pertenecen a distintos tipos.

> **Ejemplo:**
>
> Quieres ver todo lo que hay tu espacio que esté relacionado con la privacidad. Creas una consulta para buscar todos los objetos que tengan la etiqueta «privacidad». La consulta extrae objetos de diversos tipos, como proyectos, tareas, marcadores, notas, películas y artículos de prensa.

#### Relación entre colecciones y consultas

Usa una [colección](/es/organize/collections/) cuando quieras agrupar a mano objetos que carezcan de una relación clara entre sí. Las colecciones tienen el inconveniente de que su mantenimiento es manual; no se actualizan por sí mismas, por lo que pueden quedar anticuadas cuando tu espacio crezca. Por su parte, las consultas son ideales cuando los elementos del grupo comparten una regla lógica. Si puedes emplear esa regla como criterio, deja que Anytype se encargue de la gestión.

> **Ejemplo:**
>
> Quieres ver todo el contenido de tu espacio que aún no está ordenado. Creas una consulta para buscar todos los objetos que no tienen ninguna etiqueta, ordenados por fecha de modificación. De esta forma, tienes siempre al día un buzón con el contenido pendiente de organizar, por mucho que evolucione tu espacio.

## Cómo crear una consulta

Encontrarás las consultas en los mismos lugares que los tipos: la barra lateral, el menú Crear y los ajustes del canal. Y al igual que los tipos, las consultas cuentan con vistas, que funcionan de la misma manera. Para crear una consulta, puedes seguir estos pasos:

1. Haz clic en el [botón desplegable Crear](/es/create/objects/#menú-crear) de la barra lateral y selecciona **Consulta** (Query).
2. Elige uno de estos **parámetros**:
   1. [Tipo](/es/organize/types/), para obtener objetos de una misma categoría, como tareas, proyectos, libros.
   2. [Propiedad](/es/organize/properties/), para obtener objetos con una propiedad en común, como una etiqueta, un estado o un responsable.
3. Configura **filtros** y criterios de **orden**.
4. Elige un **diseño**.

![docs queries create](/assets/docs-queries-create.jpg)

![docs queries create](/assets/docs-queries-create.gif)

## Cómo usar las consultas

Puedes ver con detalle cómo gestionar las consultas y sus ajustes en la sección [Vistas](/es/organize/views/#cómo-funciona).

### Widget de la barra lateral

Las consultas se pueden [añadir a la barra lateral](/es/organize/views/#vistas-en-la-barra-lateral) en forma de widgets, igual que cualquier vista.

### Consultas insertadas

Puedes insertar consultas directamente en las páginas con el bloque **Consulta insertada**. Así podrás ver los objetos junto con tu contenido.

1. Mientras editas una página, abre el menú de comandos con el botón `+` o escribe `/consulta`:
2. Selecciona **Consulta insertada**.
3. Crea una consulta o inserta una existente.

Los tipos también se consideran una consulta, por eso aparecen también en la lista de opciones.

![docs query inline](/assets/docs-query-inline.jpg)

#### Modificación de las consultas insertadas

Las modificaciones que hagas en las vistas de una consulta insertada solo se aplican a ese bloque y no afectan a la vista principal, que se mantiene sin cambios en el [tipo](/es/organize/types/), la [consulta](/es/organize/queries/) o la [colección](/es/organize/collections/) original. Esto significa que cada objeto puede tener su propia versión de la vista insertada sin modificar nunca la original.

Por el contrario, si modificas los objetos y sus propiedades en la vista insertada, esos cambios **sí** se aplicarán al objeto y se reflejarán allá donde aparezca en todo ese espacio.

## Cómo eliminar consultas

Al igual que las vistas, las consultas son independientes de los objetos que organizan. Eliminar una consulta no afecta a los objetos subyacentes: puedes eliminar cualquier consulta de tu espacio sin perder ningún dato.

Para eliminar una consulta, ve a la sección «Consultas» de la barra lateral. Desde ahí puedes eliminarla como cualquier objeto:

* Haz clic derecho en la consulta para abrir el menú y selecciona «Mover a la papelera».
* Abre la consulta, haz clic en el menú de tres puntos de la esquina superior derecha y selecciona «Mover a la papelera».

## Notas

:::note
**No crees una consulta cuando el tipo sea suficiente.** Puedes considerar los tipos como consultas integradas. Es mejor crear consultas cuando quieres reunir objetos de varios tipos distintos.
:::

:::note
**Guarda las combinaciones de filtros como vistas, no como consultas nuevas.** Si adviertes que estás filtrando la misma consulta de la misma manera una y otra vez, guarda esos filtros como una vista. Las vistas te permiten pasar de un conjunto de filtros a otro con un solo clic.
:::

:::note
**Si quieres agrupar objetos de forma manual, usa una **[**colección**](/es/organize/collections/)**.** Las consultas están controladas por el sistema mediante reglas, mientras que las colecciones las creas tú personalmente.
:::
