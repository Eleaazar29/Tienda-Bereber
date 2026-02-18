# 🎴 Tienda Bereber

## 📖 Descripción del Proyecto
Este proyecto es un sitio web de comercio electrónico dedicado al juego de cartas de estrategia **"Mitos y Leyendas"**.

La aplicación web permite a los usuarios explorar el universo del juego, conocer las reglas básicas y acceder a una tienda virtual segmentada por categorías de productos. Incluye un sistema de carrito de compras interactivo desarrollado con JavaScript nativo.

## ✨ Características Principales

### 🏠 Página de Inicio (Landing Page)
* **Sección Hero:** Introducción visual al mundo mitológico del juego.
* **Información del Juego:** Explicación sobre la mecánica de estrategia, el uso de "Oros" y los tipos de cartas (Aliados, Talismanes, Tótem).
* **Navegación:** Menú intuitivo para acceder a la tienda, información sobre nosotros y contacto.

### 🛍️ Tienda Virtual Segmentada
El catálogo está organizado en múltiples páginas HTML interconectadas para facilitar la navegación:
* **Cartas:** Venta de sobres, mazos y cajas de expansión.
* **Colecciones:** Ediciones especiales y packs de coleccionista.
* **Ilustraciones:** Venta de arte y pósters de los personajes mitológicos.
* **Accesorios:** Tapetes de juego (Playmats) y Stickers.
* **Juegos de Mesa:** Versiones de tablero del juego.

### 🛒 Funcionalidades Técnicas (JavaScript)
* **Carrito de Compras Dinámico:**
    * Panel deslizante lateral.
    * Funcionalidad para **Añadir productos** al array del carrito.
    * Cálculo automático del **Precio Total**.
    * Botón para **Vaciar Carrito**.
    * Simulación de finalización de compra.
* **Interactividad:** Efectos *Hover* en las tarjetas de productos y transiciones suaves.

## 🛠️ Tecnologías Utilizadas
* **HTML5:** Estructura semántica de las múltiples páginas (`index`, `tienda`, `compraCartas`, etc.).
* **CSS3:** Diseño visual con paleta de colores oscuros y dorados (`#1a1a1a`, `#f4d03f`), uso de Flexbox y Grid para la disposición de productos.
* **JavaScript (Vanilla):** Lógica del lado del cliente para la gestión del estado del carrito (`main.js`).

## 📂 Estructura del Proyecto
El sitio web se divide en los siguientes archivos:
* `index.html`: Página principal.
* `tienda.html`: Hub central de categorías.
* `compra[Categoria].html`: Páginas individuales para cada tipo de producto (Cartas, Tapetes, etc.).
* `style.css`: Hoja de estilos global.
* `main.js`: Script principal para la lógica de compra.

## ⚙️ Instalación y Ejecución
1.  **Clonar el repositorio:**
    ```bash
    git clone [URL_DE_TU_REPOSITORIO]
    ```
2.  **Ejecutar:**
    * No requiere instalación de servidores (es un sitio estático).
    * Simplemente abre el archivo `index.html` en tu navegador web favorito (Chrome, Edge, Firefox).

---
**Desarrollado por:** Eleazar - 2025-2026.
