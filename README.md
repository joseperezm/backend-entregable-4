# Proyecto de Actualización con Websockets y Handlebars

Este proyecto ha sido actualizado para incluir funcionalidades de Websockets y Handlebars. Permite una visualización en tiempo real de la lista de productos utilizando Socket.io y Handlebars.

## Instrucciones de Prueba

Sigue estos pasos para probar las nuevas funciones:

### Requisitos Previos

- Asegúrate de tener Node.js y npm instalados en tu máquina.

### Instalación

1. Clona este repositorio en tu máquina local:

    ```bash
    git clone <URL_del_repositorio>
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd entregable-3
    ```

3. Instala las dependencias:

    ```bash
    npm install
    ```

### Ejecución del Servidor

1. Inicia el servidor:

    ```bash
    npm start
    ```

2. Abre tu navegador y visita [http://localhost:8080](http://localhost:8080).

### Prueba de Funcionalidades

1. Visualización en Tiempo Real:
    - Accede a [http://localhost:8080/realtimeproducts](http://localhost:8080/realtimeproducts) para ver la lista de productos en tiempo real.
    - Agrega nuevos productos utilizando el formulario. Observa cómo la lista se actualiza automáticamente.
    - Intenta eliminar un producto haciendo clic en el botón "Eliminar". La eliminación también se reflejará en tiempo real.

2. Lista de Productos:
    - Accede a [http://localhost:8080](http://localhost:8080) para ver la lista estática de productos.
