# Vistas

Las vistas son distintas miradas sobre tu contenido. Sirven para visualizar la información de la forma que más te convenga sin alterar el contenido subyacente. Los [tipos](types.md), las [consultas](queries.md) y las [colecciones](collections.md) usan vistas para presentar su contenido.

> **Una analogía**: imagínate un edificio con cien personas dentro. Puedes cambiar la forma en que las miras, pero todas seguirán dentro del edificio. Puedes poner a todas las personas vestidas de rojo en el vestíbulo y dejar a las demás ocultas en el sótano, o bien ordenarlas de la más alta a la más baja en una larga fila.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Properties Views.gif" alt=""/><figcaption></figcaption></figure></div>

## Qué significa esto

1. Las vistas te ofrecen perspectivas nuevas de tu contenido, como un calendario para elementos relacionados con el tiempo o una galería para el contenido más visual. En resumen, puedes presentar y mostrar el mismo contenido de varias formas distintas.
2. Gracias a las vistas, no necesitas duplicar el contenido nunca. Puedes partir del mismo conjunto de objetos y reorganizarlos según necesites en cada ocasión.

## Cómo funciona

Una vista tiene tres componentes principales:

1. **Diseño**: la estructura visual de los objetos; por ejemplo, un diseño de galería. [Más ejemplos](views.md#vistas-en-tipos-consultas-y-colecciones).
2. **Filtros**: el conjunto de objetos que se muestra, como un filtro para objetos con estado «completado».
3. **Orden**: la forma en que se suceden los objetos, como un orden alfabético.

### Diseños

Los diseños organizan tus [objetos](../create/objects/) y sus [propiedades](properties.md) de una forma cómoda para trabajar con ellos, como una serie de eventos en un calendario o un montón de tareas en un tablero kanban. Aquí tienes algunos ejemplos de distintos [diseños en acción](views.md#vistas-en-tipos-consultas-y-colecciones).

<table><thead><tr><th width="130.99609375">Opciones</th><th>Ideal para</th><th>Opciones propias</th></tr></thead><tbody><tr><td><strong>Lista</strong></td><td>Filas verticales simples</td><td>Compacta, Estándar</td></tr><tr><td><strong>Cuadrícula</strong></td><td>Similar a una hoja de cálculo</td><td>Ajustar contenido</td></tr><tr><td><strong>Calendario</strong></td><td>Organización por fecha y hora</td><td>Propiedad de fecha</td></tr><tr><td><strong>Kanban</strong></td><td>Agrupación y gestión de proyectos</td><td>Agrupar por, Colorear columnas, Portada</td></tr><tr><td><strong>Galería</strong></td><td>Gran efecto visual</td><td>Portada, Tamaño de tarjeta, Icono, Ajustar medios</td></tr><tr><td><strong>Gráfico</strong></td><td>Relaciones interconectadas</td><td>Ajustes del gráfico</td></tr></tbody></table>

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views How Layout.jpg" alt=""/><figcaption></figcaption></figure></div>

{% hint style="warning" %} Algunas vistas no están disponibles en el móvil. {% endhint %}

### Filtros

Los filtros limitan los objetos de una vista a los que cumplen ciertas condiciones, es decir, ocultan parte de los datos en esa vista. Un filtro tiene tres partes:

1. **Propiedad**: la propiedad que se comprueba (como «estado» o «fecha final»).
2. **Condición**: la clase de comprobación (por ejemplo, «no es» o «es mayor que»).
3. **Valor**: el valor que se busca en la propiedad (como «en curso» u «hoy»).

Aquí tienes algunos filtros de ejemplo para proyectos:

* Para ver lo que vence hoy: `Fecha final` `es` `Hoy`
* Para ocultar los proyectos completados: `Estado` `no es` `Listo`
* Para encontrar elementos de prioridad alta: `Prioridad` `contiene` `Urgente` y `Alta`

Puedes aplicar varios filtros; se combinan con el operador lógico «Y». Para aplicar filtros más avanzados con el operador lógico «O», agruparlos y usar condiciones complejas, consulta [Filtros avanzados](../advanced/feature-list-by-platform/advanced-filters.md).

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Filters.jpg" alt=""/><figcaption></figcaption></figure></div>

### Orden

Los criterios de orden determinan qué objetos aparecen primero en la vista. No ocultan ningún dato; solo deciden el orden en que se colocan. Cuando aplicas un criterio de orden, tienes que elegir la dirección:

1. **Ascendente** irá de menor a mayor (de la A a la Z o de fechas pasadas a futuras, por ejemplo).
2. **Descendente** irá de mayor a menor (de la Z a la A o con la fecha más lejana primero).

Aquí tienes algunos criterios de ejemplo para proyectos:

* Para ver primero lo más urgente: `Fecha final` ordenado de forma `Ascendente`.
* Para ver la actividad más reciente: `Modificado por última vez` ordenado de forma `Ascendente`.
* Para ver más valorado: `Valoración` ordenado de forma `Descendente`.

Puedes aplicar varios criterios de orden a una vista. Se aplicará el primer criterio, seguido del segundo, y así sucesivamente.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Sort.jpg" alt=""/><figcaption></figcaption></figure></div>

## Cómo crear y gestionar las vistas

Las vistas se usan en los [tipos](types.md), las [consultas](queries.md) y las [colecciones](collections.md). Encontrarás un conjunto de vistas por defecto, pero puedes añadir las vistas personalizadas que quieras. Como las vistas solo afectan a la presentación de los datos, puedes modificarlas, eliminarlas o reorganizarlas sin peligro de alterar la información subyacente.

#### Cómo crear una vista

1. Abre cualquier tipo, consulta o colección desde la barra lateral.
2. Haz clic en el botón «+» de la cabecera de vista, bajo el área del título.
3. En «Ajustes de vista», puedes asignarle un título, seleccionar el diseño y aplicar filtros/criterios de orden.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Create.jpg" alt=""/><figcaption></figcaption></figure></div>

#### Cambiar los ajustes de la vista

Haz clic en el botón «Ajustes de vista», que es el icono situado junto al botón «Nuevo».

* **Diseño**: elige el diseño que usarás para visualizar los objetos.
* **Propiedades**: elige las propiedades que se muestran y su posición, y añade otras nuevas.
* **Filtrar y ordenar**: aplica filtros y criterios de orden a la vista.
* **Duplicar vista**: crea un clon de la vista con los mismos ajustes.
* **Eliminar vista**: elimina la vista (no afecta a los objetos).

Para cambiar el orden de las vistas, haz clic en el nombre de la vista que quieras mover y arrástrala.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Settings.jpg" alt=""/><figcaption></figcaption></figure></div>

## Cómo usar las vistas

### Vistas en tipos, consultas y colecciones

Todas las vistas siguen un proceso de tres pasos: elegir un diseño, definir algún filtro y ordenar con un criterio. Aquí tienes unos ejemplos de vistas que podrías crear:

* **Diseño de galería** filtrado solo con tus **proyectos activos** ordenados por **prioridad**.
* **Diseño de calendario** con **todos tus proyectos** según su **fecha límite**.
* **Diseño de cuadrícula** filtrado solo con **proyectos asignados a ti** ordenados por **actividad más reciente**.
* **Diseño de kanban** filtrado por **proyectos etiquetados como Importante** agrupados por **estado actual**.

<div><figure><img src="../../.gitbook/assets/Docs Views Grid.jpg" alt=""/><figcaption><p>Diseño de cuadrícula</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs Views List.jpg" alt=""/><figcaption><p>Diseño de lista</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs Views Kanban.jpg" alt=""/><figcaption><p>Diseño de kanban</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs Views Gallery.jpg" alt=""/><figcaption><p>Diseño de galería</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs Views Calendar.jpg" alt=""/><figcaption><p>Diseño de calendario</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Docs Views Graph.jpg" alt=""/><figcaption><p>Diseño de gráfico</p></figcaption></figure></div>

### Vistas en la barra lateral

Puedes añadir vistas a tu barra lateral para tenerlas a mano. Son lo que conocemos como [widgets.md](../basics/sidebar/widgets.md "mention").

1. Usa el botón de tres puntos de la esquina superior derecha y selecciona **Anclar al canal**.
2. Haz clic derecho en el elemento de la barra lateral.
3. En la sección del menú «Vista», selecciona **Como en el objeto**.
4. Si la vista no aparece, pasa el puntero sobre el icono y haz clic en la flecha desplegable para mostrarla.

En la barra lateral también puedes alternar entre las distintas vistas que hayas creado.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Sidebar.gif" alt=""/><figcaption></figcaption></figure></div>

### Vistas en objetos

Puedes insertar vistas directamente en las páginas con los bloques **Consulta insertada** y **Colección insertada**. Así podrás ver los objetos junto con tu contenido.

1. Mientras editas una página, abre el menú de comandos con el botón `+` o el atajo `/inser`:
2. Selecciona **Consulta insertada** para añadir un [tipo](types.md) o una [consulta](queries.md), o **Colección insertada** para añadir una [Colección](collections.md).

Las modificaciones que hagas en las vistas de una consulta o colección insertada solo se aplican a ese bloque y no afectan a la vista principal, que se mantiene sin cambios en el [tipo](types.md), la [consulta](queries.md) o la [colección](collections.md) original. Esto significa que cada objeto puede tener su propia versión de la vista insertada sin modificar nunca la original.

Por el contrario, si modificas los objetos y sus propiedades en la vista insertada, esos cambios sí se aplicarán al objeto y se reflejarán en todo ese espacio.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Inline.gif" alt=""/><figcaption></figcaption></figure></div>

### Buscar en las vistas

En la barra de herramientas de herramientas de la vista, junto al botón «Nuevo», hay un icono de búsqueda. Sirve para filtrar temporalmente los objetos de la vista según el texto que introduzcas. Es muy útil para refinar aún más la selección de objetos que aparecen en la vista.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Search.jpg" alt=""/><figcaption></figcaption></figure></div>

### Edición de objetos en lote

Puedes modificar varios [objetos](../create/objects/) al mismo tiempo para cambiar su tipo y sus propiedades o eliminarlos de un golpe. Es mejor hacerlo en una vista con el diseño de cuadrícula, pero también funciona con otros diseños.

1. Abre la vista desde la barra lateral.
2. Selecciona todos los objetos que quieres modificar. Hay dos formas de hacerlo:
   1. Usa el atajo `Cmd/Ctrl + K` para seleccionarlos todos.
   2. Haz clic y arrastra para crear un cuadro de resaltado.
   3. Haz clic en el control de la izquierda (solo en diseños de cuadrícula y de lista) y añade más objetos a la selección con `Mayús + clic`.
3. Haz clic derecho y elige una de estas acciones:
   1. Cambiar tipo
   2. Editar propiedades
   3. Añadir a colección
   4. Exportar
   5. Duplicar
   6. Mover a la papelera

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Bulk Edit.gif" alt=""/><figcaption></figcaption></figure></div>

### Arrastrar objetos de una vista a otra

Si arrastras un objeto de una vista y lo colocas en otra, sus propiedades se actualizan automáticamente para coincidir con los filtros de esa vista. Por ejemplo, puedes arrastrar una tarea desde la vista «Todas» hasta la vista «Completadas» y su propiedad «Estado» pasará a ser «Listo».

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/Docs Views Drag.gif" alt=""/><figcaption></figcaption></figure></div>

## Cómo eliminar vistas

Las vistas son independientes de los objetos que organizan. Eliminar una vista no afecta a los objetos subyacentes: puedes eliminar cualquier vista de un tipo, consulta o colección sin perder ningún dato.

Para eliminar una vista, haz clic derecho sobre ella para abrir el menú. También puedes eliminarla desde los ajustes de vista, en su barra de herramientas.

## Notas

{% hint style="info" %} **Pon a tus vistas un nombre relacionado con su diseño o filtro**. Los nombres descriptivos, como «Tareas prioritarias» y «Proyectos archivados», te ayudarán a distinguir en seguida lo que estas viendo. {% endhint %}

{% hint style="info" %} **Cuando quieras editar objetos en lote, es mejor configurar primero los filtros de la vista** para que solo muestre los objetos que vas a modificar. Así podrás seleccionarlos con más rapidez. También puedes crear una [consulta](queries.md) para hacerlo. {% endhint %}
