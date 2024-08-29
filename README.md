# Backend del Sistema Móvil de Navegación y Asistencia de Rutas en Entornos Cerrados

## Descripción General

Este proyecto de backend proporciona la infraestructura necesaria para soportar una aplicación móvil de navegación y asistencia de rutas en entornos cerrados. La aplicación permite crear mapas en 3D y generar guías de rutas a partir de imágenes, utilizando tecnologías avanzadas para el procesamiento de imágenes y la renderización 3D.

El backend ha sido desarrollado utilizando .NET Core 8, siguiendo una arquitectura en capas para garantizar un alto rendimiento, seguridad, escalabilidad, y facilidad de mantenimiento.

## Tecnologías Utilizadas

- **.NET Core 8**: Framework utilizado para desarrollar el backend. Ofrece alto rendimiento, multiplataforma y es ideal para construir aplicaciones web y APIs robustas.
- **Entity Framework Core**: ORM utilizado para interactuar con la base de datos relacional. Permite un manejo eficiente de las operaciones CRUD y consultas más complejas con LINQ.
- **SQL Server**: Base de datos relacional utilizada para almacenar datos persistentes de la aplicación, como información de usuarios, logs de actividad, y datos de rutas.
- **Swagger**: Herramienta utilizada para generar documentación interactiva de la API RESTful, permitiendo a los desarrolladores y usuarios probar los endpoints directamente desde la interfaz.
- **AutoMapper**: Biblioteca para realizar mapeos automáticos entre los modelos de datos y los DTOs (Data Transfer Objects), simplificando el código y reduciendo errores.
- **JWT (JSON Web Tokens)**: Utilizado para la autenticación y autorización de usuarios, proporcionando una capa de seguridad robusta y escalable.
- **Docker**: Contenedor utilizado para el despliegue del backend, asegurando que el entorno de desarrollo y producción sean consistentes y fáciles de gestionar.
- **Azure DevOps**: Plataforma utilizada para la integración continua y el despliegue continuo (CI/CD) del backend, facilitando la automatización de pruebas y despliegues.

## Arquitectura del Backend

El backend sigue una **Arquitectura en N Capas** que permite una separación clara de responsabilidades y facilita el mantenimiento y la escalabilidad del sistema. Las capas principales son:

1. **Capa de Presentación (API Controllers)**: Maneja las solicitudes HTTP entrantes, interactúa con la lógica de negocio y devuelve las respuestas HTTP apropiadas.
2. **Capa de Lógica de Negocio (Services)**: Contiene la lógica empresarial del sistema. Aquí se procesan las reglas de negocio, validaciones y se orquestan las interacciones entre la capa de presentación y la
