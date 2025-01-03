# Alura Geek - Reto HTML, CSS, JS y JSON-Server

Este proyecto fue desarrollado como parte del reto de **Alura Geek**, con el objetivo de poner a prueba habilidades en HTML, CSS, JavaScript y la implementación de un servidor JSON con **json-server**. La aplicación incluye una interfaz estática que permite gestionar productos mediante un formulario y una vista dinámica de los productos existentes.

## Características

- **Vista de productos**:
  - Visualización de los productos disponibles en el servidor.
  - Opción para eliminar productos individualmente.

- **Formulario de productos**:
  - Permite agregar nuevos productos con sus respectivos datos.
  - Botón para limpiar las casillas del formulario.

## Requisitos previos

- Tener **Node.js** instalado en tu sistema.

## Cómo ejecutar el proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Anggie2020/alura-geek.git
   cd alura-geek
   ```

2. **Instalar las dependencias**:
   ```bash
   npm install
   ```

3. **Ejecutar el servidor JSON**:
   ```bash
   npx json-server --watch db.json --port 5500
   ```

4. **Abrir la vista estática**:
   - Abre el archivo `index.html` en tu navegador para visualizar la aplicación.

## Funcionalidades principales

1. **Visualización de productos**:
   - Los productos se listan en el lado izquierdo de la pantalla.

2. **Agregar productos**:
   - Completa el formulario en el lado derecho y presiona el botón para agregar un nuevo producto.

3. **Eliminar productos**:
   - Cada producto tiene un botón de eliminar para quitarlo individualmente del listado.

4. **Limpiar formulario**:
   - Botón para limpiar los campos del formulario sin agregar datos.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- JSON-Server

