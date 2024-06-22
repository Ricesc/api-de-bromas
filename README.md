# API de Bromas

Una API RESTful simple para administrar bromas usando Node.js, Express y MongoDB.

## Descripción general

La API de bromas proporciona endpoints para crear, leer, actualizar y eliminar bromas. Es un ejemplo básico de una aplicación CRUD creada con:

-   Node.js y Express para el backend.
-   MongoDB como base de datos.
-   Mongoose para el modelado de objetos de MongoDB.

## Endpoints de la API

-   Obtener todas los bromas: `GET /api/jokes`
-   Obtener una broma específica: `GET /api/jokes/:_id`
-   Crear una nueva broma: `POST /api/jokes/new`
-   Actualizar una broma: `PUT /api/jokes/update/:_id`
-   Eliminar una broma: `DELETE /api/jokes/delete/:_id`
