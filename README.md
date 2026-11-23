# Prácticas de Full Stack Python — Codo a Codo

Repositorio de apuntes, ejercicios y ejemplos realizados durante el curso de
**Full Stack Python de Codo a Codo**. Reúne material de distintas clases y
unidades para consultar y practicar los conceptos del recorrido, desde los
fundamentos de programación hasta el desarrollo web del lado del cliente y las
bases de datos.

> **Importante:** este repositorio es una colección educativa, no un único
> producto ni una aplicación lista para desplegar. Cada carpeta contiene
> ejercicios autónomos; algunos proyectos integradores enlazan varias
> tecnologías y recursos locales.

## Contenidos

### Algoritmos y lógica — `pseint/`

Algoritmos introductorios en PSeInt para practicar entrada y salida de datos,
operadores, condicionales simples y anidados, selección por casos y ciclos
`Mientras` y `Para`. Incluye ejercicios como el cálculo del área de un
triángulo, un inicio de sesión y un cajero automático.

### HTML — `HTML/`

Ejemplos de estructura y contenido web: texto, listas, enlaces y rutas,
elementos en bloque y en línea, imágenes, favicon, tablas con celdas combinadas,
audio, video e `iframe`. También hay ejercicios de etiquetas semánticas,
formularios, controles de selección y páginas integradoras. La carpeta
`HTML/Para Netlify/` contiene un pequeño sitio estático con páginas de inicio,
contacto y presentación.

### CSS — `CSS/`

Prácticas de estilos y maquetación que abarcan:

- Selectores, clases e identificadores, cascada y especificidad.
- Colores, tipografías, unidades y fuentes web.
- Modelo de caja, márgenes, rellenos, bordes, posicionamiento y `z-index`.
- Pseudoclases, pseudoelementos, transformaciones, transiciones y animaciones.
- Diseño adaptable con media queries y breakpoints.
- Flexbox y CSS Grid, incluidas áreas, líneas, alineación y patrones de diseño
  responsive.
- Bootstrap: contenedores, grillas, columnas, componentes y plantillas.

### JavaScript — `JS/`

Ejercicios que acompañan páginas HTML y recorren los fundamentos del lenguaje:
variables, tipos y conversiones, operadores, condicionales, ciclos, funciones,
ámbito, funciones flecha, objetos, cadenas, números y arreglos. También se
practican JSON, almacenamiento en `localStorage` y `sessionStorage`, el DOM,
eventos, creación y modificación de contenido HTML, formularios y validaciones.
Hay ejemplos integradores, entre ellos un sitio con productos y acciones para
administrarlos.

### Vue.js y consumo de datos — `VUE/`

Material de introducción a Vue.js: interpolación y directivas (`v-bind`,
`v-for`, `v-if`, `v-show`, `v-model`, `v-on`), eventos, instancias, componentes,
propiedades computadas y watchers. Los ejemplos de la tercera clase practican
JavaScript asíncrono y consumo de APIs con Fetch y Axios, tanto con promesas
como con `async`/`await`. También hay ejemplos de sitios multipágina (MPA) y de
una interfaz de una sola página (SPA), además de ejercicios que presentan datos
de recetas, vinos, superhéroes y Rick and Morty.

### Python — `PYTHON/`

Ejercicios de Python organizados por clase y tema. Se trabajan sintaxis básica,
variables, entrada y salida, operadores, cadenas, estructuras condicionales e
iterativas, colecciones (listas, tuplas, conjuntos y diccionarios) y funciones
(parámetros, valores de retorno, argumentos opcionales y funciones lambda).
El recorrido continúa con programación orientada a objetos: clases, objetos,
atributos, encapsulamiento, getters y setters, variables de clase, herencia,
polimorfismo y clases abstractas. También hay ejemplos de módulos y paquetes,
módulos de la biblioteca estándar y manejo de errores y excepciones. En varias
carpetas se incluyen consignas, resúmenes o material complementario en PDF y
presentaciones.

### Bases de datos y SQL — `BBDD/`

Consultas y ejercicios SQL, scripts para crear y cargar bases de datos de
práctica y diagramas entidad-relación. Los temas incluyen filtros, orden,
agrupamientos y funciones de agregación, `HAVING`, funciones escalares,
subconsultas y combinación de tablas mediante `JOIN` (incluidos `INNER`,
`LEFT` y `RIGHT JOIN`). Las carpetas de guías incluyen consignas y soluciones.

## Tecnologías y herramientas

| Área | Tecnologías |
| --- | --- |
| Lógica | PSeInt |
| Estructura web | HTML |
| Presentación y diseño responsive | CSS, Flexbox, CSS Grid y Bootstrap |
| Programación en el navegador | JavaScript, DOM, JSON y Web Storage |
| Interfaces reactivas y datos | Vue.js, Fetch API y Axios |
| Programación y orientación a objetos | Python |
| Bases de datos | SQL |

El material incluye archivos fuente y recursos locales (imágenes, audio, video,
documentos y bibliotecas de ejemplo). Las versiones de las herramientas no
están centralizadas en una configuración única: por ejemplo, no hay un solo
`package.json` o archivo de dependencias que instale o ejecute todo el
repositorio.

## Organización

```text
.
├── BBDD/       # Bases de datos, scripts SQL, guías y diagramas
├── CSS/        # CSS, responsive, Flexbox, Grid y Bootstrap
├── HTML/       # Ejemplos y ejercicios de HTML
├── JS/         # Fundamentos de JavaScript, DOM y ejercicios integradores
├── PYTHON/     # Fundamentos, funciones, POO y excepciones
├── VUE/        # Vue.js, SPA/MPA y consumo de APIs
├── pseint/     # Algoritmos introductorios
└── README.md
```

Los nombres de carpetas identifican el área, la clase o el tema. Dentro de
varios ejemplos, los archivos `.html` cargan sus archivos `.css`, `.js` e
imágenes de forma relativa; conviene conservar la estructura de carpetas al
abrirlos.

## Cómo recorrer y ejecutar las prácticas

- **HTML, CSS, JavaScript y Vue:** abrir el archivo `.html` del ejemplo en un
  navegador. Mantener juntos sus recursos vinculados. Para ejemplos que
  consumen servicios externos, se requiere conexión a Internet; algunos
  navegadores también pueden limitar solicitudes realizadas al abrir archivos
  directamente, por lo que puede ser necesario servir la carpeta con un
  servidor web local.
- **Python:** ejecutar cada archivo `.py` con una instalación de Python. Algunos
  ejercicios están pensados para ejecutarse desde su carpeta porque importan
  módulos o paquetes locales.
- **SQL:** abrir los scripts `.sql` con un cliente compatible y ejecutarlos en
  una base de datos de práctica. Revisar primero si el archivo crea tablas,
  inserta datos o supone que una base ya está cargada.
- **PSeInt:** abrir los archivos `.psc` en PSeInt para leer o ejecutar los
  algoritmos.

No existe un comando único de instalación, pruebas o ejecución para todo el
repositorio: se trata de prácticas independientes y se trabaja con la
herramienta correspondiente a cada tecnología.
