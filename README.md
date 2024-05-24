Documentación del GoatFramework
===============================

Introducción
------------

El GoatFramework es un framework MVC minimalista inspirado en Laravel, diseñado para facilitar el desarrollo de aplicaciones web con una estructura clara y sencilla. Utiliza Node.js para la gestión de modelos, vistas y controladores, y proporciona una configuración simple para la conexión a bases de datos.

Características Principales
---------------------------

-   **Estructura MVC**: Separación clara entre Modelos, Vistas y Controladores.
-   **Configuración Sencilla**: Configuración rápida y fácil para la conexión a bases de datos.
-   **CLI Integrado**: Herramientas de línea de comandos para la generación de modelos, vistas y controladores.
-   **Routing Simplificado**: Manejo de rutas de forma intuitiva.
-   **Basado en Node.js**: Aprovecha la flexibilidad y rendimiento de Node.js.

Instalación
-----------

### Requisitos Previos

-   Node.js (versión 12 o superior)
-   NPM (gestor de paquetes de Node.js)

### Pasos de Instalación

1.  **Clonar el Repositorio**: Clona el repositorio desde GitHub y navega al directorio del proyecto:

    ```plaintext
    git clone https://github.com/tu-usuario/GoatFramework.git
    cd GoatFramework
    ```

2.  **Instalar las Dependencias**: Ejecuta el siguiente comando para instalar las dependencias del proyecto:

    ```plaintext
    npm install
    ```

3.  **Configurar el Archivo .env**: Configura tu archivo `.env` para la conexión a la base de datos:

    ```plaintext
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=nombre_base_de_datos
    DB_USERNAME=usuario
    DB_PASSWORD=contraseña
    ```

Uso Básico
----------

### Comandos CLI

El GoatFramework incluye una CLI para facilitar la generación de componentes del framework.

-   **Crear un Modelo**:

    ```plaintext
    node goat model NombreDelModelo
    ```

-   **Crear una Vista**:

    ```plaintext
    node goat view NombreDeLaVista
    ```

-   **Crear un Controlador**:

    ```plaintext
    node goat controller NombreDelControlador
    ```

### Iniciar el Servidor

Para iniciar el servidor de desarrollo:

```plaintext
npm start
```

El servidor se ejecutará en http://localhost:3000.