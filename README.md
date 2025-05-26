# Progreso y gestión para el desarrollo local

Este proyecto es una página web desarrollada exclusivamente con HTML y CSS, diseñada para mostrar unas vistas de un sitio donde pueden aplicar para ser beneficiarios de subsidios educativos, acceder a una biblioteca virtual, y a clases virtuales, este proyecto lo visualizamos, para facilitar el acceso a la educación a población vulnerable.

## Características

- Desarrollado exclusivamente con HTML y CSS (sin JavaScript ni frameworks)
- Diseño responsive que se adapta a diferentes tamaños de pantalla
- Estructura semántica utilizando las etiquetas HTML5 apropiadas
- Metodología BEM (Block, Element, Modifier) para nombrar clases CSS
- Paleta de colores personalizable mediante variables CSS
- Estructura de archivos organizada y modular
- Biblioteca estructurada con paginas de HTML y CSS, y tambien imagenes. 
- Página de visualización de componentes para facilitar su implementación

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

Diego arango -- Log in -- Registro --

Daniela mejia -- Clases virtuales --

Luis campis -- Biblioteca virtual --



En esta plantilla hicimos los cambios de nombres en las carpetas de pages about por login, y servicios por registro, ademas se agregaro una carpeta con subcarpetas donde se encuentran los logos e imagenes de cada una de nuestras paginas, hicimos un cambio de colores, se agrego  la pagina de clases virtuales, biblioteca y subsidios, se modificaron los enlaces de la barra de navegacion del header, eliminamos el enlace de la seccion de bienvenida junto con los enlaces rapidos del footer.

En nuestro sitio web llamado PROGRESO Y GESTIÓN PARA EL DESARROLLO LOCAL (PGDL) quisimos hacer un sitio donde el usuario principal puede acceder a subsidios de estudio, una biblioteca virtual con material interactivo y clases virtuales, y donde los profesores pueden apoyar el estudiante con actualizaciones para un aprendizaje mas completo.
