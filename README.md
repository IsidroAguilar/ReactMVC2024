## Descripción

El proyecto ReactMVC2024 es un sistema básico que utiliza las tecnologías React, MVC y .Net Core 8 para implementar las operaciones CRUD en una aplicación web. Proporciona una interfaz de usuario basada en React para interactuar con una base de datos, permitiendo al usuario crear, leer, actualizar y eliminar registros.

## Características

El proyecto CRUDMVCReactNetCore incluye las siguientes características:

- Interfaz de usuario basada en React: Permite al usuario interactuar con el sistema de forma intuitiva y amigable.
- Operaciones CRUD: Permite realizar las operaciones básicas de creación, lectura, actualización y eliminación de registros en la base de datos.
- Arquitectura MVC: Utiliza el patrón de arquitectura Modelo-Vista-Controlador para estructurar y organizar el código de la aplicación.
- .Net Core: Utiliza el framework .Net Core para el desarrollo del backend de la aplicación.
- Base de datos: Utiliza una base de datos para almacenar y gestionar los datos de la aplicación.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado lo siguiente:

- Node.js: [Descargar e instalar Node.js](https://nodejs.org).
- .Net Core SDK: [Descargar e instalar .Net Core SDK](https://dotnet.microsoft.com/download).

## Configuración

Sigue los pasos a continuación para configurar y ejecutar el proyecto:

1. Clona el repositorio del proyecto en tu máquina local: `git clone https://github.com/IsidroAguilar/ReactMVC2024.git`
2. Navega hasta el directorio del proyecto: `cd CRUDMVCReactNetCore`
3. Instala las dependencias del frontend: `cd ClientApp` y luego `npm install`
4. Regresa al directorio raíz del proyecto: `cd ..`
5. Configura la cadena de conexión a la base de datos en el archivo `appsettings.json`.
6. Abre una terminal y ejecuta el siguiente comando para crear la base de datos: `dotnet ef database update`.
7. Ejecuta el proyecto con el siguiente comando: `dotnet run`.

Una vez que hayas seguido estos pasos, podrás acceder a la aplicación en tu navegador a través de la URL `http://localhost:5000`.

## Contribuciones

¡Las contribuciones son bienvenidas! Si quieres mejorar este proyecto, siéntete libre de enviar pull requests. Asegúrate de seguir las mejores prácticas de desarrollo y proporcionar una descripción clara de los cambios que realizas.

## Licencia

Este proyecto se distribuye bajo la licencia [MIT](https://opensource.org/licenses/MIT). Siéntete libre de utilizar, modificar y distribuir el código fuente de acuerdo con los términos de esta licencia.

## Contacto

Si tienes alguna pregunta o sugerencia relacionada con este proyecto, no dudes en ponerte en contacto conmigo a través de mi dirección de correo electrónico: isidro.aguilar94@gmail.com.

¡Gracias por tu interés en el proyecto CRUDMVCReactNetCore! Espero que sea útil en tu aprendizaje del desarrollo web con .Net Core
