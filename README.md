# Arquitectura

La arquitectura de este repositorio está diseñada para ser modular y escalable. A continuación, se describe la estructura principal del repositorio y cómo se conectan los procesos entre sí:

## Componentes de la interfaz de usuario

- `App.tsx`: Es el punto de entrada de la aplicación y se encarga de renderizar el componente `AppContainer`.
- `AppContainer.tsx`: Es el contenedor principal de la aplicación y se encarga de renderizar el componente `NavigationContainer`.
- `NavigationContainer.tsx`: Se encarga de manejar la navegación entre pantallas utilizando React Navigation.
- `HomeScreen.tsx`: Representa la pantalla de inicio de la aplicación y muestra una lista de espacios.
- `SpaceDetailScreen.tsx`: Representa la pantalla de detalles de un espacio y muestra información detallada sobre el espacio seleccionado.
- `PomodoroTimerScreen.tsx`: Representa la pantalla del temporizador de Pomodoro y permite iniciar, pausar y reiniciar el temporizador.
- `SignInScreen.tsx`: Representa la pantalla de inicio de sesión y permite a los usuarios iniciar sesión en la aplicación.
- `SettingsScreen.tsx`: Representa la pantalla de ajustes y permite a los usuarios cambiar la configuración de la aplicación.
- `ProfileScreen.tsx`: Representa la pantalla de perfil y muestra la información del usuario.
- `CreateSpaceScreen.tsx`: Representa la pantalla para crear un espacio y permite a los usuarios crear un nuevo espacio.
- `JoinSpaceScreen.tsx`: Representa la pantalla para unirse a un espacio y permite a los usuarios unirse a un espacio existente.
- `ChatScreen.tsx`: Representa la pantalla de chat y permite a los usuarios enviar y recibir mensajes en un espacio específico.

## Contexto de aplicación

- `AppContext.tsx`: Es el contexto de aplicación que se utiliza para gestionar el estado global de la aplicación.

## Utilerías y funciones auxiliares

- `helpers.ts`: Contiene varias utilerías y funciones auxiliares, como `formatTimeForHome`, `formatTimeDetailed`, `formatDate`, `formatDateDetailed`, `formatPomodoroTime`, `formatPomodoroTimeDetailed`, `generateRandomId`, `generateRandomColor`, `generateRandomName`, `generateRandomDescription`, `generateRandomImage`, `generateRandomDate`, `generateRandomTime`, `generateRandomPomodoroTime`, `generateRandomPomodoroType`, `generateRandomPomodoroRule`, `generateRandomSession`, `generateRandomChatMessage`, etc.

## Conexiones con el repositorio de API

- `routers/routers.py`: Define las rutas de la API y se encarga de manejar las solicitudes y respuestas.
- `utils/auth_utils.py`: Contiene utilerías relacionadas con la autenticación y verificación de usuarios, como la generación de tokens de verificación, la creación de mensajes de recuperación de usuario y la verificación de tokens.
- `utils/database.py`: Contiene funciones y clases relacionadas con la conexión a la base de datos, como la obtención de la sesión de la base de datos, la creación de tablas y la ejecución de consultas SQL.

## Conexiones con la base de datos

- `querys/tablas.sql`: Contiene consultas SQL para crear las tablas de la base de datos, incluyendo `tbl_users`, `tbl_sessions`, `tbl_pomodoro_rules`, `tbl_pomodoro_types` y `tbl_pause_tracking`.

En resumen, la arquitectura de este repositorio incluye componentes de la interfaz de usuario, un contexto de aplicación, utilerías y funciones auxiliares, así como conexiones con el repositorio de API y la base de datos. Estos procesos se conectan entre sí para brindar una experiencia de usuario completa
