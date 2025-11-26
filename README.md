# Arquitectura

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

## Conexiones entre componentes

- `AppContainer.tsx` se conecta con `NavigationContainer.tsx` para manejar la navegación entre pantallas.
- `HomeScreen.tsx` se conecta con `SpaceDetailScreen.tsx` para mostrar los detalles de un espacio seleccionado.
- `SpaceDetailScreen.tsx` se conecta con `PomodoroTimerScreen.tsx` para iniciar, pausar y reiniciar el temporizador de Pomodoro.
- `SignInScreen.tsx` se conecta con `SettingsScreen.tsx` para cambiar la configuración de la aplicación.
- `ProfileScreen.tsx` se conecta con `CreateSpaceScreen.tsx` y `JoinSpaceScreen.tsx` para crear y unirse a espacios.
- `ChatScreen.tsx` se conecta con la base de datos para enviar y recibir mensajes en un espacio específico.

Estos son los componentes principales de la aplicación y cómo se conectan entre sí.
