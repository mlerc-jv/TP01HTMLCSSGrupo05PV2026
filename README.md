# Trabajo Practico N°1 - PROGRAMACION VISUAL 2026

GRUPO 5 | Comision 2

Integrantes:

-ARAMAYO PAREDES, Lourdes Daniela ( @luxi777 )

-CABRERA, Maia Luisana - ( @lucabrera565 )

-CARRILLO, Marianela Valentina Abril - ( @abrilcarrillo )

-MAIDANA, Antonella Mariel - ( @antoto17 )

-MERUVIA, Jimena Virginia - ( @mlerc-jv )

-QUISPE MOLLOJA, Guadalupe Belen - ( @Guada-q ) 

## HTML

Este trabajo consiste en crear la plataforma de "Gestion de Proyectos", esta conformado por 5 archivos html, los cuales comparten una misma barra de navegacion (nav) el cual permite que el usuario pueda moverse libremente por las secciones de nuestro sitio y un (footer) que incluye informacion del proyecto. 

index.html: Es la pagina principal del sitio, se utiliza (header) para la Bienvenida, contiene informacion relevante para el usuario como estadisticas (total de proyectos, tareas que continuan pendientes y mensajes recibidos) utilizando (article), tambien novedades que muestra actividad de los usuarios.

proyectos.html: Corresponde a la seccion de Explorador de Proyectos (header), incluye un formulario con filtro (aside) para organizar los proyectos segun: categoria, año, estado (pendiente o finalizado), dentro de (section) se presentan distintos proyectos, cada uno dentro de (article) junto a informacion basica de cada uno y una imagen representando cada tema.

detalle.html: Corresponde a una vista individual del proyecto (header), para mostrar fecha de inicio y autores utilizamos (p), con la etiqueta (ul) se utiliza para crear lista desordenada. Dentro de ella los elementos (li) para cada item. En este caso el item contiene enlaces a los recursos de los proyectos (a)

perfil.html: Representa la seccion de perfil (header), en (section) incluye una descripcion del objetivo del trabajo. Contiene una tabla (table) para organizar los datos requeridos  de los integrantes.

tareas.html: Esta es una seccion adicional a la plataforma, consiste en la gestion de tareas (header) de cada proyecto educativo que haya, se utilizan filtros (aside) para organizar las tareas (proyecto, estado, fecha), dentro de (section) se muestran las tareas, que estan organizadas por (article).

## CSS

Se aplicaron estilos a cada archivo HTML utilizando CSS, con el objetivo de mejorar la presentación de nuestra pagina

Cabe aclarar que en este grupo, cada integrante trabajó independientemente en el diseño de estas, para que puedan aplicar sus conocimientos de forma libre.

index.css: Fueron empleadas las tres formas para aplicar estilos y el uso de clases. En (:root) se definió la paleta de colores de esta sección. Se utilizó flexbox para la organización de elementos (header, navbar, tarjetas) y CSS grid para la estructura general (main). Por ultimo, para que el usuario tenga una experiencia más amigable se implementaron estados interactivos (:hover, :focus, :active)

proyectos.css: Se manejaron las tres formas de aplicar estilos y los dos tipos de selectores. Tambien se utilizó (:root)para definir los colores de este sector. Se aplicó grid en (main) para dividir la pagina en dos columnas(aside y section), y Flexbox en (nav). En la interactividad de esta se aplicaron los tres estados (:hover, :focus, :active).

detalle.css: Se empleó unicamente el estilo externo, junto con el uso de selectores por etiquetas. Se utilizó (:root) para los colores de la pagina. Se aplicó grid en (main) para organizar las secciones del contenido, y flexbox en el (nav). Se incorporó dos estados de interactividad (:focus, :active)

style.css: Es el estilo de perfil.html. Se manejó principalmente el estilo externo, junto a ambos selectores (clases e id). Se utilizaron variables en (:root) para definir colores y tipografia de la pagina. Se aplicó grid en (body) para la estructura de la misma (header, nav, main, footer), y flexbox en menú y tarjetas. Se emplearon los tres estados de interactividad (:hover, :active, :focus).

tareas.css: En esta seccion se aplicó el estilo externo y el uso de selector por clases. En (:root) se definió la paleta de colores de la pagina, también se manejó grid en (main) para dividir la pagina en dos columnas (aside y section), y flexbox en (navbar y tareas-contenedor). En cuanto a la interactividad, se aplicó el estado (:hover).