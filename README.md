# Progreso y gestión para el desarrollo local

Este proyecto es una página web desarrollada exclusivamente con HTML y CSS, diseñada para mostrar unas vistas de un sitio donde pueden aplicar para ser beneficiarios de subsidios educativos, acceder a una biblioteca virtual, y a clases virtuales, este proyecto lo visualizamos, para facilitar el acceso a la educación a población vulnerable.

## Descripción del proyecto

- Este proyecto esta enfocado en tres problemáticas principales que se presenta a nivel global en el ámbito estudiantil, como son temas relacionados con patrocinios estudiantiles, incentivar el habito de lectura sin necesidad de incurrir en la compra de libros y por ultimo facilitar el acceso a las clases virtuales.

- Basados en las tres problemáticas, el patrocinio es importante porque permite el acceso al estudio para personas con bajos recursos, población vulnerable  y tener espacios e implementos adecuados para el óptimo desarrollo de las actividades. La biblioteca es importante ya que permite el acceso a material didáctico sin necesidad de gasto económico y complementar el conocimiento; Tomar o reforzar las clases de forma virtual para evitar la inasistencia.

- Evitar la deserción escolar por escases de recursos y falta de habilidades de competencia.


## Características

- La primera funcionalidad del aplicativo seria un espacio donde el estudiante se postula por medio de un formulario para acceder a un apoyo económico para que pueda acceder a educación superior y tener competencias laborales.

- La segunda funcionalidad seria un espacio donde los estudiantes puedan acceder a material de apoyo, donde se les brindara la opción de tomar cursos y leer libros sin ningún costo.

La tercera funcionalidad seria un espacio donde el estudiante puede ver las clases de manera virtual para así mantener una buena asistencia y no afecte su rendimiento académico, además podrá reforzar lo visto en clase.


## Estructura del Proyecto

```
/
├── assets/
│   ├── css/
│   │   ├── biblioteca.css   # Estilos específicos para la página Biblioteca
│   │   ├── clasesvirtuales.cs  # Estilos globales y variables
│   │   ├── contact.css      # Estilos específicos para la página Contacto
│   │   ├── index.css        # Estilos específicos para la página Principal
│   │   ├── login.css        # Estilos específicos para la página Login
│   │   ├── registro.css     # Estilos específicos para la página Registro
│   │   ├── styles.css       # Estilos específicos para la página Styles
│   │   └── subsidios.css    # Estilos específicos para la pagina Clases subsidios
│   ├── images/                  # Carpeta para almacenar imágenes
|   |   ├── iconos               # Imagenes de contenedores para la pagina principal
|   |   ├── Logo                 # Imagen para el header
|   |   └── logoclasesvirtuales  # Imagen para contenedor de clases virtuales
├── pages/
│   ├── biblioteca.html     # Página Biblioteca
│   ├── clasesvirtuales.html # Página Clases virtuales
│   ├── contac.html         # Página Contacto
│   ├── login.html          # Página Log in
│   ├── registro.html       # Página Registro
|   └── subsidios.html      # Página subsidios
├── index.html              # Página principal
└── README.md               # Este archivo
```

## Páginas Incluidas

- **Inicio (index.html)**: Página principal con secciones de subsidios, bibloteca virtual y clases virtuales.
- **Log in  (login.html)**: Formulario de logueo para usuarios ya registrados a nuestro sitio web.
- **Registro (registro.html)**: Formulario para el registro de nuevos usuarios a nuestro sitio web.
- **Contacto (contact.html)**: Formulario de contacto, información de contacto, y mapa.
- **Subsidios (subsidios.html)**: pagina de subsidios con enlace a contaco.
- **Biblioteca (biblioteca.html)**: pagina de biblioteca con secciones para diferentes categorias de estudio.  
- **clases virtuales (clasesvirtuales.html)**:Pagina de clases virtuales con mensaje de bienvenida y secciones para clases virtuales.

## Personalización
Usamos un tema con el color mas parecido a nuestro boceto. 

### Colores

La paleta de colores se puede personalizar fácilmente modificando las variables CSS en el archivo `assets/css/styles.css`. Las principales variables son:

```css
:root {
    /* Colores base sofisticados */
    --color-primary: #8e44ad;
    /* Púrpura elegante */
    --color-secondary: #f39c12;
    /* Dorado vibrante */
    --color-accent: #c0392b;
    /* Rojo vino intenso */
    --color-dark: #1c1c1c;
    /* Negro suave */
    --color-light: #f8f8f8;
    /* Gris perla */
```

### Tipografía

La tipografía también se puede personalizar modificando las variables correspondientes en el mismo archivo:

```css
:root {
    --font-family-base: 'Arial', 'Helvetica', sans-serif;
    --font-family-heading: 'Arial', 'Helvetica', sans-serif;
    /* ... tamaños de fuente ... */
}
```

## Metodología BEM

Este proyecto utiliza la metodología BEM (Block, Element, Modifier) para nombrar las clases CSS, lo que facilita la comprensión y el mantenimiento del código. Ejemplos:

- `.header` (bloque)
- `.header__logo` (elemento)
- `.nav__link--active` (modificador)

## Responsive Design

El diseño se adapta a diferentes tamaños de pantalla mediante el uso de media queries. Los principales breakpoints son:

- **Móvil**: hasta 480px
- **Tablet**: hasta 768px
- **Desktop**: más de 768px



## Créditos
Pedro zamora -- Subsidios -- Index -- Contacto -- README.md --
- HTML5: Se hizo la creación de la pagina de subsidios con estructura HTML5 y CSS, con etiquetas semanticas <html><head><body><header><h1><nav><ul><li><main><section><div><img><a><h2><p> con la cuales se estructuro conservando las buenas practicas para hacer un encabezado con una imagen y una barra de navegación, para navegar entre paginas, el contenido principal de la pagina contiene un titulo, una tarjeta con una imagen y un parrafo en la parte superior, y un parrafo con un boton que enlaza a contacto en la parte inferior.

- CSS:Se reutilizaron las clases para el header y el footer de nuestra pagina y para cada una de nuestras paginas se crearon clases propias para dar estilo a las mismas.



Diego arango -- Log in -- Registro --

Daniela mejia -- Clases virtuales --

Luis campis -- Biblioteca virtual --



En esta plantilla hicimos los cambios de nombres en las carpetas de pages about por login, y servicios por registro, ademas se agregaro una carpeta con subcarpetas donde se encuentran los logos e imagenes de cada una de nuestras paginas, hicimos un cambio de colores, se agrego  la pagina de clases virtuales, biblioteca y subsidios, se modificaron los enlaces de la barra de navegacion del header, eliminamos el enlace de la seccion de bienvenida junto con los enlaces rapidos del footer.

En nuestro sitio web llamado PROGRESO Y GESTIÓN PARA EL DESARROLLO LOCAL (PGDL) quisimos hacer un sitio donde el usuario principal puede acceder a subsidios de estudio, una biblioteca virtual con material interactivo y clases virtuales, y donde los profesores pueden apoyar el estudiante con actualizaciones para un aprendizaje mas completo.
