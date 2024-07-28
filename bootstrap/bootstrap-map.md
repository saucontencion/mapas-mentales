## 1. Clases Principales y Estructura de la Página

- **Grid System**
  - `container`, `container-fluid`: Define el contenedor principal de la página, controla el ancho y el padding.
  - `row`: Define una fila dentro del contenedor, para organizar columnas.
  - `col-*`, `col-sm-*`, `col-md-*`, `col-lg-*`, `col-xl-*`: Define el tamaño de las columnas dentro de una fila, responsivo según el tamaño de la pantalla.
## 2. Estilos y Clases de Utilidad

- **Colores y Estilos**
  - **`.text-*`**: Define colores de texto.
  - **`.font-weight-bold`, `.font-italic`**: Define estilos de fuente como negrita o cursiva.
  - **`.bg-*`**: Define colores de fondo para elementos.
    - **Colores de fondo básicos:**
      - **`.bg-primary`**: Color de fondo primario (generalmente azul).
      - **`.bg-secondary`**: Color de fondo secundario (generalmente gris).
      - **`.bg-success`**: fondo para indicar éxito (verde).
      - **`.bg-danger`**: fondo para indicar peligro o error (rojo).
      - **`.bg-warning`**: para indicar advertencia (amarillo).
      - **`.bg-info`**: proporcionar información (azul claro).
    - **Colores adicionales:**
      - **`.bg-light`**: Color de fondo claro.
      - **`.bg-dark`**: fondo oscuro.
      - **`.bg-white`**: blanco.
      - **`.bg-transparent`**: Fondo transparente (sin color de fondo).

## 3. Estilos y Clases de Utilidad

- **Espaciado**
  - `.p-*`: Define relleno (padding).
    
  - `.m-*`: Define márgenes (margin).
  - **Dirección:**
    1. `t` - Para espaciado-top.
          - pt-1
          - pt-3
    2. `b` - Para espaciado-bottom.
          - mb-2
          - mt-5
    3. `s` - espaciado-left o espaciado-right.
         - ps-auto 
         - ms-auto 
    4. `e` - espaciado-right o padding-left
    5. `x` - left y right.
    6. `y` - top y bottom.
    7. `auto` Sin especificación espaciado en los cuatro lados.
  - **Tamaño:**
     1. `0` - Elimina el espaciado.
     1. `1` - (por defecto) Establece el padding al valor base multiplicado por 0.25.
     1. `2` - (por defecto) Establece el padding al valor base multiplicado por 0.5.
     1. `3` - (por defecto) Establece el padding al valor base.
     1. `4` - (por defecto) Establece el padding al valor base multiplicado por 1.5.
     1. `5` - (por defecto) Establece el padding al valor base multiplicado por 3.     
     1. `auto` - Establece el padding a `auto`.

- **Bordes y Formas**
  - `.rounded`, `.rounded-*`: Define bordes redondeados.
  - `.rounded-circle`: Define una forma circular.
  - `.rounded-pill`: Define una forma de píldora.
  
## 4 Clases de Visualización
#### - **Clase:** `.d-none`
- **Descripción:**
  - Oculta completamente el elemento y sus descendientes.
- **Características:**
  - No ocupa espacio en el flujo del documento.
  - No es accesible mediante navegadores o dispositivos.

#### **Clase:** `.d-inline`
- **Descripción:**
  - Permite que el elemento se muestre en línea, junto a otros elementos en la misma línea.
- **Características:**
  - Ocupa solo el espacio necesario para el contenido.

#### `.d-inline-block`
- **Descripción:**
  - Permite que el elemento se muestre como un bloque en línea, manteniendo el flujo en línea.
- **Características:**
  - Ocupa el espacio que necesite el contenido, pero se comporta como un bloque en términos de alineación y tamaño.

####  `.d-block`

  - Permite que el elemento se muestre como un bloque independiente en el flujo del documento.

  - Ocupa todo el ancho disponible y comienza en una nueva línea.

#### `.d-flex`

  - Transforma el contenedor en un contenedor flexible que permite el uso de flexbox.

  - Los elementos dentro del contenedor se pueden organizar de manera flexible según las reglas de flexbox.

#### `.d-inline-flex`
  - Transforma el contenedor en un contenedor flexible en línea.

  - Los elementos dentro del contenedor se organizan de manera flexible en línea, según las reglas de flexbox.  



## 5. Componentes de Navegación

- **Navbar**
  - `.navbar`, `.navbar-expand-*`: Define un navbar responsivo con opciones para expandirse según el tamaño de la pantalla.
  - `.navbar-brand`: Logo o título en el navbar.
  - `.navbar-nav`, `.nav-item`, `.nav-link`: Define la estructura de navegación con elementos de lista.
  - `.dropdown`, `.dropdown-toggle`, `.dropdown-menu`: Permite crear menús desplegables dentro del navbar.

## 6. Componentes de Contenido

- **Carousel**
  - `.carousel`, `.carousel-item`: Contenedor principal y elementos individuales del carousel.
  - `.carousel-control-prev`, `.carousel-control-next`: Flechas de control para navegar entre elementos del carousel.
  - `.carousel-indicators`: Indicadores de navegación para el carousel.

- **Cards**
  - `.card`: Contenedor principal para un elemento de tarjeta.
  - `.card-header`, `.card-body`, `.card-footer`: Secciones dentro de una tarjeta para encabezado, cuerpo y pie.
  - `.card-title`, `.card-subtitle`: Títulos y subtítulos dentro de una tarjeta.
  - `.card-img-top`, `.card-img-bottom`: Imágenes en la parte superior o inferior de una tarjeta.
  - `.card-group`, `.card-deck`: Agrupa tarjetas horizontal o verticalmente sin espacios.

## 7. Modales y Otros Componentes

- **Modals**
  - `.modal`, `.modal-dialog`, `.modal-content`: Estructura básica de un modal.
  - `.modal-header`, `.modal-body`, `.modal-footer`: Encabezado, cuerpo y pie de página dentro del modal.
  - `.modal-title`: Título del modal.
  - `.modal-dismiss`, `.modal-close`: Cerrar el modal.

- **Alertas**
  - `.alert`, `.alert-*`: Define alertas con diferentes estilos y colores.
  - `.alert-dismissible`: Permite cerrar las alertas con un botón de cierre.

## 8. Comportamiento y Interactividad

- **Collapse**
  - `.collapse`, `.collapsing`, `.collapse.show`: Define un elemento colapsable.
  - `.collapse-toggle`, `.data-toggle`: Elementos que activan el colapso.

- **Scrollspy**
  - `.scrollspy`, `.navbar-scroll`: Monitorea la posición del usuario y activa elementos de la barra de navegación según la posición del desplazamiento.

## 9. Integración con JavaScript

- **jQuery y Popper.js**
  - Funcionalidades adicionales para elementos dinámicos como tooltips, popovers, etc.

## 10. Ejemplos y Prácticas Recomendadas

- **Uso en Práctica**
