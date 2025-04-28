# MisRecetasApp:

Aplicación web que permite a las personas registrar y gestionar sus recetas.

Se podrá añadir, modificar y eliminar recetas, cada una con información detallada.

La aplicación deberá estar desarrollada en JavaScript puro, utilizando HTML y CSS para la interfaz.

## Funcionalidades Requeridas:
CRUD (Crear, Leer, Actualizar, Eliminar):

Crear: Permitir al usuario añadir una nueva receta con los siguientes campos:

- Nombre de la receta.
- Ingredientes.
- Instrucciones de preparación.
- Tiempo de preparación.
- Número de porciones.
- Categoría (Desayuno, Almuerzo, Cena, Postre, etc.).
- Nivel de dificultad (Fácil, Medio, Difícil).

## Validaciones:
- El nombre de la receta no puede estar vacío.
- El tiempo de preparación debe ser un número válido y positivo.
- El número de porciones debe ser un número entero positivo.
- La categoría y nivel de dificultad deben seleccionarse de una lista predefinida.

**Leer:** Mostrar una lista de todas las recetas almacenadas con la información relevante.

**Actualizar:** Permitir al usuario modificar los detalles de una receta existente.

**Eliminar:** Permitir al usuario eliminar una receta.

**Filtros y Búsqueda:**

Implementar un sistema de filtros para que el usuario pueda ver sus recetas por:

- Categoría (Ej. Desayuno, Almuerzo, etc.).
- Nivel de dificultad (Fácil, Medio, Difícil).
- Incluir una barra de búsqueda para encontrar una receta por su nombre.

## Validación de Datos:
- Implementar validaciones básicas para asegurar que los datos ingresados sean correctos (Ej. Tiempo de preparación debe ser un número válido, el número de porciones debe ser un entero positivo, etc.).

## Interfaz de Usuario:
- Diseñar una interfaz de usuario amigable y responsiva que permita una fácil navegación y uso de la aplicación.
- Asegurarse de que la aplicación sea accesible desde dispositivos móviles y de escritorio.

## Persistencia de Datos:
- Utilizar LocalStorage para guardar los datos del usuario, de manera que, al cerrar y reabrir la aplicación,
los datos no se pierdan.

## Requerimientos Técnicos:

Para desarrollar la división del proyecto FrontEnd se deben tener los siguientes puntos en cuenta:
- El aplicativo debe manejar de manera correcta el modelo documento-objeto (DOM) para un buen
funcionamiento por parte del motor del navegador.
- Debe ser responsive y manejar UI/UX a lo largo de todo el proyecto.
La entrega de este examen se realizará grupos de 1 persona, donde se debe anexar un enlace a un repositorio en
GitHub llamado “Examen_JavaScript_Apellido1Nombre1” que contenga el código de la aplicación construida en
JavaScript, HTML y CSS. En este mismo repositorio, debe contener los siguientes archivos:
- Documentación general del proyecto a nivel de Readme.md
- Archivos que den funcionalidad al programa principal de HTML Y CSS mediante JavaScript.
Para desarrollar la división del proyecto FrontEnd se deben tener los siguientes puntos en cuenta:
- Debe ser responsive y manejar UI/UX a lo largo de todo el proyecto.
- Se tendrá en cuenta la creatividad y redacción del contenido.

## Técnologías a Utilizar:
<ul>
    <li>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML" width="15"/>
        </a>
        HTML5.
    </li>
    <li>
        <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS" width="15"/>
        </a>
        CSS3.
    </li>
    <li> 
        <a href="https://developer.mozilla.org/es/docs/Web/JavaScript" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="15"/>
        </a>
        JavaScript (ES6+).
    </li>
    <li>
        <a href="https://www.json.org/json-es.html" target="_blank" rel="noreferrer">
            <img src="https://www.json.org/img/json160.gif" alt="JSON" width="15"/>
        </a>
        JSON.
    </li>
    <li>
        <a href="https://daringfireball.net/projects/markdown/" target="_blank" rel="noreferrer">
            <img src="https://cdn.commonmark.org/uploads/default/original/2X/3/366f3614de6996d79a131fdf9b41ed7d65cfe181.png" alt="Markdown" width="15"/>
        </a>
        Markdown.
    </li>
    <li>
        💾<code>localStorage</code> para persistencia de datos en el navegador.
    </li>
    <li>  
        <a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" width="15"/>
        </a>
        VS Code.
    </li>
    <li> 
        <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="15"/>
        </a>
        Git.
    </li>
    <li> 
        <a href="https://github.com/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="GitHub" width="15"/>
        </a>
        GitHub.
    </li>
</ul>

## 📂 Estructura:

```bash
├── 📁 css/                                        # Archivos de CSS.
│ ├── 📝 style.css                                 # Estilo de la página principal.
│ └── 📝 variables.css                             # Variables para las hojas de estilo.
├── 📁 js/                                         # Archivos de JS.
│ ├── 📝 main.js                                   # Script de la página principal.
├── 📁 storage/                                    # Recursos gráficos.
│ ├── 📁 fonts/                                    # Fuentes para el texto.
│ └── 📁 img/                                      # Imágenes.
├── 📝 index.html                                  # Página principal del sitio (Landing Page).
├── 📝 LICENSE.md                                  # Licencia del proyecto.
└── 📝 README.md                                   # Documentación del proyecto.
```

## Licencia:

Este proyecto cuenta con una [Licencia MIT](./LICENSE.md).
