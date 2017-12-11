# MY WEBSITE

* **Track:** _Common Core_
* **Curso:** _Crea tu propia red social_
* **Unidad:** _La web desde un móvil_

## Objetivo
Realizar una página a nuestro gusto. El diseño se puede realizar como mejor nos parezca, pero se debe mantener la estructura de la página mostrada en la parte inferior. Se debe realizar con un grid (cualquiera pero que no sea un framework como Bootstrap o Materialize)

## Alumna
* Maria Cristina Ortiz Villafuerte.

## Descripción

Se muestra la website **REACH COFFE**, es una organización encargada de la  elaboración de café de la mejor calidad y en aroma sabor, asi mismo, brinda servicios servicios eficientes (y rentables) en todos los procesos de la cadena productiva y agroindustrial del café.

La página esta adaptada tanto para diseño mobile, tablet, ipad como desktop.

Para resolver dicho reto se hizo lo siguiente:

* Se creó un documento **HTML** donde se observa la aplicación de **grid system** para tener un sistema organizado y una experiencia unforme tanto en vista mobile, tablet y desktop, la division es como sigue:

  - _div.container_: Contiene todas las filas cono sus columnas, en las cuales encontramos los contenidos.

  - _div.row_  : existen tres filas principales:

    - **Primera**: Contiene al _**header**_, el cual contiene la fila _row menu-bar_,quien contiene las columnas(3) donde se halla 3 etiquetas nav ("reach coffe", "menu amburguesa para vista mobile", "menu para la vista desktop y tablet); y la fila _row background-image_ quien contiene la columna donde esta la imagen de fondo.

    - **Segunda**: Contiene a la _**Section.first-section**_ donde estan las columnas(dos) que contienen a "what we do" y "contact us ".

    - **Tercera**: Contiene a la _**Section.second-section**_ el cual tiene un fila donde estan las columnas(3) que contienen a "proces service", "Green Coffee Exportation" y "Our products".

    -**Cuarta**: Contiene al _**footer**_ dentro de una columna.

* Se creó un archivo **main.css** y se adaptó el archivo **grid.css** facilitado por la junior teacher donde se encuentran todos los estilos aplicados a todas la partes del body del documento HTML. Se utilizó la técnica de css3 **media query** (condicional) para tener una vista uniforme tanto para mobile, tablet, y desktop.


## Estructuras usadas para el reto

![my pagina.desktop](assets/docs/desktop.png)

![my pagina.mobile](assets/docs/mobile.png)
