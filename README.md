
# ProyectoGestorEventos

## 📋 Descripción

**ProyectoGestorEventos** es una aplicación web diseñada para facilitar la organización y gestión de eventos y tareas en equipos colaborativos. Desarrollada con tecnologías modernas como **ASP.NET Core**, **Blazor**, **Entity Framework Core**, y **PostgreSQL**, la aplicación ofrece una interfaz intuitiva y funcionalidades robustas para administrar eventos, asignar tareas, enviar notificaciones en tiempo real y más.

## 🚀 Características

- **Gestión de Eventos:** Crear, editar, eliminar y visualizar eventos con detalles completos.
- **Asignación de Tareas:** Asignar tareas a miembros del equipo y hacer seguimiento de su progreso.
- **Autenticación y Autorización:** Sistema de inicio de sesión seguro para administradores y usuarios.
- **Notificaciones en Tiempo Real:** Recibir actualizaciones instantáneas sobre cambios en eventos y tareas.
- **Interfaz Responsiva:** Diseño adaptado para dispositivos móviles y de escritorio.
- **API Gateway:** Gestión eficiente de solicitudes API mediante Ocelot.
- **Contenerización:** Despliegue fácil y escalable utilizando Docker y Kubernetes (opcional).

## 🛠 Tecnologías Utilizadas

- **Frontend:**
  - Blazor/Razor Pages
  - Bootstrap, HTML, CSS
- **Backend:**
  - ASP.NET Core
  - Entity Framework Core
- **Base de Datos:**
  - PostgreSQL
- **API Gateway:**
  - Ocelot
- **Notificaciones:**
  - SignalR
- **Seguridad:**
  - JWT (JSON Web Tokens)
  - HTTPS/TLS

## 📥 Instalación

Sigue estos pasos para configurar y ejecutar el proyecto localmente:

1. **Clonar el Repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/ProyectoGestorEventos.git
    cd ProyectoGestorEventos
    ```

2. **Configurar la Base de Datos:**
    - Asegúrate de tener PostgreSQL instalado.
    - Crea una base de datos llamada `GestorEventos`.
    - Ejecuta el script SQL proporcionado en el archivo `database.sql` para crear las tablas.

3. **Configurar Variables de Entorno:**
    - Crea un archivo `.env` en la raíz del proyecto.
    - Añade las variables necesarias, como la cadena de conexión a la base de datos.
    ```env
    DATABASE_URL=postgres://usuario:contraseña@localhost:5432/GestorEventos
    JWT_SECRET=tu_secreto_jwt
    ```

4. **Ejecutar la Aplicación:**
    ```bash
    dotnet run --project ProyectoGestorEventos
    ```

5. **Acceder a la Aplicación:**
    - Abre tu navegador y ve a `http://localhost:5000`.

## 🎨 Diseños y Mockups

![Mockup de la Página de Inicio](https://link-a-tu-imagen.com/mockup-inicio.png)

## 📅 Gestión de Proyectos

La gestión detallada de las actividades y el progreso del proyecto se encuentra en nuestro [Gestor de Proyectos en Notion](https://www.notion.so/tu-enlace-de-proyecto).

## 📜 Licencia

Este proyecto está licenciado bajo la **[Licencia Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)**.

**Resumen de la Licencia:**
- **Reconocimiento (BY):** Debes dar crédito de manera adecuada, proporcionar un enlace a la licencia y indicar si se hicieron cambios.
- **No Comercial (NC):** No puedes utilizar el material para fines comerciales.
- **CompartirIgual (SA):** Si remixas, transformas o construyes sobre el material, debes distribuir tus contribuciones bajo la misma licencia que el original.

## 📫 Contacto

- **Nombre:** Jerson Enrique Ramos
- **Correo Electrónico:** jerson_ramos1310@yahoo.es
- **GitHub:** [JersonRamos10](https://github.com/tu-usuario)


---

