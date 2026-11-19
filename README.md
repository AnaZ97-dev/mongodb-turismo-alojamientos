# Base de Datos NoSQL: Gestión de Alojamientos Turísticos (MongoDB)

Proyecto de modelado y gestión de datos no relacionales utilizando **MongoDB**. Incluye una guía de instalación del entorno, la creación de una base de datos documental y operaciones CRUD (Creación, Lectura, Actualización y Borrado) básicas.

## 🛠️ Tecnologías y Herramientas
*   **Base de Datos NoSQL:** MongoDB Community Server (v8.x)
*   **Interfaz Gráfica:** MongoDB Compass
*   **Shell:** Mongosh
*   **Formato de datos:** JSON

## 🎯 Funcionalidades y Conceptos Aplicados
El proyecto se divide en dos partes:

### 1. Configuración del Entorno
*   Instalación y configuración de MongoDB Community Server y su interfaz gráfica (Compass).
*   Configuración de las variables de entorno del sistema para poder ejecutar `mongosh` desde la terminal.
*   Creación de la base de datos `turismo` y la colección `alojamientos`.

### 2. Operaciones con Documentos
*   **Importación de datos:** Carga de un archivo `alojamientos.json` con múltiples documentos que contienen información detallada de alojamientos (id, nombre, teléfono, dirección, número de habitaciones, precios, etc.).
*   **Inserción:** Uso del comando `insertOne()` desde la consola `mongosh` para añadir un nuevo documento especificando un ID concreto (`id: 110`).

## 🚀 Cómo ejecutar el proyecto
1. Asegúrate de tener instalado MongoDB Server y Compass.
2. Abre MongoDB Compass y conéctate a `localhost:27017`.
3. Crea la base de datos `turismo` y la colección `alojamientos`.
4. Importa el archivo `alojamientos.json` en la colección.
5. Abre la terminal (PowerShell), conéctate con `mongosh`, usa `use turismo` y ejecuta las sentencias de inserción.
