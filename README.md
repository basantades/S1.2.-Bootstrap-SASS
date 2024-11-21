
```markdown
# S1.2. Bootstrap&SASS

## Descripción del Proyecto

Este proyecto implementa un diseño web responsivo utilizando HTML, CSS, **Bootstrap**, y **Sass**. Además de un diseño flexible con **Flexbox**, se incorporan varias funcionalidades interactivas como menús fijos, menús móviles a pantalla completa, validación de formularios, animaciones con **hover** y un **carrusel** de imágenes.

### Características

- **Diseño Responsivo**: El layout se adapta a diferentes tamaños de pantalla (escritorio, tablet y móvil) mediante media queries.
- **Flexbox**: Uso de Flexbox para crear un diseño flexible y alineado.
- **Bootstrap 5**: Integración de Bootstrap para componentes predefinidos, como botones, formularios, menús, y más.
- **Sass**: Utilización de Sass para organizar y optimizar los estilos CSS, permitiendo una mayor modularidad y reutilización de código.
- **Menú Fijo (Fixed Navbar)**: Implementación de un menú de navegación que se mantiene fijo en la parte superior de la pantalla al hacer scroll.
- **Menú Móvil Fullscreen**: Menú desplegable que cubre toda la pantalla en dispositivos móviles.
- **Validación de Formularios**: Implementación de validaciones en los formularios utilizando las clases de Bootstrap y JavaScript para garantizar que los datos ingresados sean correctos.
- **Carrusel de Imágenes**: Implementación de un carrusel de imágenes funcional usando el componente de Bootstrap.

## Estructura del Proyecto

La estructura de archivos y carpetas es la siguiente:

```
/Proyecto-Responsive
├── index.html                      # Página principal con el contenido HTML
├── /css                            # Carpeta para archivos CSS compilados
│   ├── main.css                    # Estilos CSS compilados desde Sass
│   ├── main.scss                   # Archivo principal de Sass que importa otros archivos parciales
├── /images                         # Carpeta de imágenes
├── /js                             # Archivos JavaScript
│   ├── bootstrap.bundle.min.js     # Funcionalidad JavaScript de Bootstrap
│   └── calidacion-forms.js         # Funcionalidad JavaScript para vlidar formulario
├── .gitignore                      # Archivo que especifica qué archivos deben ser ignorados por Git
└── README.md                       # Este archivo
```

- **index.html**: Contiene el código HTML que estructura la página, incluyendo la inclusión de Bootstrap, Sass compilado, y los scripts JavaScript.
- **main.css**: Estilos CSS compilados desde Sass.
- **main.scss**: Archivo principal de Sass que organiza y estructura los estilos del proyecto.
- **scripts.js**: Contiene la lógica JavaScript para interactuar con elementos como el menú, validación de formularios, y el carrusel de imágenes.

## Tecnologías Utilizadas

- **HTML5**: Lenguaje de marcado utilizado para la estructura de la página web.
- **CSS3**: Para los estilos visuales y la creación del diseño responsivo.
- **Bootstrap 5**: Framework de diseño que proporciona componentes predefinidos para acelerar el desarrollo.
- **Sass**: Preprocesador CSS que permite escribir estilos más organizados y reutilizables.
- **JavaScript**: Lenguaje de programación utilizado para la interactividad, como el menú desplegable y la validación de formularios.
- **jQuery** (si es necesario para algunos componentes de Bootstrap): Para facilitar la manipulación del DOM y la interactividad.

## Instalación

   ```bash
   git clone https://github.com/basantades/S1.2.-Bootstrap-SASS.git
   ```