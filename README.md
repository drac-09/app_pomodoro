# Arquitectura

La arquitectura de este repositorio está diseñada para ser modular y escalable. A continuación, se describe la estructura principal del repositorio:

## Componentes

El repositorio contiene varios componentes React que se utilizan para construir la interfaz de usuario de la aplicación. Algunos de los componentes clave incluyen:

- `App.tsx`: Este componente es el punto de entrada de la aplicación y se encarga de renderizar el componente `AppContainer`.
- `AppContainer.tsx`: Este componente es el contenedor principal de la aplicación y se encarga de renderizar el componente `NavigationContainer` de React Navigation.
- `NavigationContainer.tsx`: Este componente se encarga de manejar la navegación entre pantallas utilizando React Navigation.
- `HomeScreen.tsx`: Este componente representa la pantalla de inicio de la aplicación y muestra una lista de espacios.
- `SpaceDetailScreen.tsx`: Este componente representa la pantalla de detalles de un espacio y muestra información detallada sobre el espacio seleccionado.
- `PomodoroTimerScreen.tsx`: Este componente representa la pantalla del temporizador de Pomodoro y permite iniciar, pausar y reiniciar el temporizador.
- `SignInScreen.tsx`: Este componente representa la pantalla de inicio de sesión y permite a los usuarios iniciar sesión en la aplicación.
- `SettingsScreen.tsx`: Este componente representa la pantalla de ajustes y permite a los usuarios cambiar la configuración de la aplicación.
- `ProfileScreen.tsx`: Este componente representa la pantalla de perfil y muestra la información del usuario.
- `CreateSpaceScreen.tsx`: Este componente representa la pantalla para crear un espacio y permite a los usuarios crear un nuevo espacio.
- `JoinSpaceScreen.tsx`: Este componente representa la pantalla para unirse a un espacio y permite a los usuarios unirse a un espacio existente.
- `ChatScreen.tsx`: Este componente representa la pantalla de chat y permite a los usuarios enviar y recibir mensajes en un espacio específico.

## Contexto de aplicación

El repositorio utiliza un contexto de aplicación llamado `AppContext` para gestionar el estado global de la aplicación. El contexto se define en el archivo `context/AppContext.tsx` y se exporta para que pueda ser utilizado en otros componentes.

## Utilerías y funciones auxiliares

El repositorio incluye varias utilerías y funciones auxiliares en el archivo `utils/helpers.ts`. Algunas de las funciones clave incluyen:

- `formatTimeForHome`: Esta función se utiliza para formatear el tiempo en formato de tiempo completo (HH:MM:SS) para mostrar en la pantalla de inicio.
- `formatTimeDetailed`: Esta función se utiliza para formatear el tiempo en formato de tiempo completo (HH:MM:SS) para mostrar en la pantalla de detalles del espacio.
- `formatDate`: Esta función se utiliza para formatear la fecha en formato de fecha completa (DD/MM/YYYY) para mostrar en la pantalla de detalles del espacio.
- `formatDateDetailed`: Esta función se utiliza para formatear la fecha en formato de fecha completa (DD/MM/YYYY) para mostrar en la pantalla de detalles del espacio.
- `formatPomodoroTime`: Esta función se utiliza para formatear el tiempo del temporizador de Pomodoro en formato de tiempo completo (HH:MM:SS) para mostrar en la pantalla del temporizador de Pomodoro.
- `formatPomodoroTimeDetailed`: Esta función se utiliza para formatear el tiempo del temporizador de Pomodoro en formato de tiempo completo (HH:MM:SS) para mostrar en la pantalla de detalles del espacio.
- `generateRandomId`: Esta función se utiliza para generar un identificador aleatorio para los espacios y mensajes.
- `generateRandomColor`: Esta función se utiliza para generar un color aleatorio para los espacios.
- `generateRandomName`: Esta función se utiliza para generar un nombre aleatorio para los espacios.
- `generateRandomDescription`: Esta función se utiliza para generar una descripción aleatoria para los espacios.
- `generateRandomImage`: Esta función se utiliza para generar una imagen aleatoria para los espacios.
- `generateRandomDate`: Esta función se utiliza para generar una fecha aleatoria para los espacios.
- `generateRandomTime`: Esta función se utiliza para generar un tiempo aleatorio para los espacios.
- `generateRandomPomodoroTime`: Esta función se utiliza para generar un tiempo aleatorio para los tempor
