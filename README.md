# Hábitos de Estudio

App móvil web (PWA) hecha a partir de los mockups de Figma "Mockups APP".
Se abre desde un enlace en el navegador del celular, sin instalar nada, y se puede
agregar a la pantalla de inicio para usarla como una app normal.

## Qué incluye

- Iniciar sesión, crear cuenta, recuperar y cambiar contraseña.
- Inicio con racha de días, promedio del semestre, número de materias, progreso por materia y métodos de estudio.
- Mi perfil: cambiar nombre, contraseña y foto (cámara o galería), eliminar perfil y cerrar sesión.
- Mis materias, Tareas y Flashcards: crear, editar, eliminar (con confirmación) y mensajes de éxito.
- Calendario semanal con horario de clases y tareas del día.
- Simulador de notas: calcula la nota que necesitas en el último periodo para aprobar con 3.0.
- Pomodoro con iniciar, pausar, descansar y ajuste de tiempo.

Los datos se guardan en el navegador del mismo celular (localStorage). No usa servidor.
"Continuar con Google" abre una cuenta de demostración, porque una app sin servidor no puede validar cuentas de Google.
La app no bloquea capturas ni grabación de pantalla, así que al compartir pantalla todo se ve.

## Publicarla con GitHub Pages

1. En el repositorio entra a **Settings → Pages**.
2. En "Build and deployment" elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
3. Espera uno o dos minutos. La app queda en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Instalarla en el celular

- **Android (Chrome):** abre el enlace, toca el menú ⋮ y luego **Agregar a pantalla de inicio** (o **Instalar app**).
- **iPhone (Safari):** abre el enlace, toca **Compartir** y luego **Agregar a pantalla de inicio**.

## Probarla en el computador

Abre una terminal en esta carpeta y ejecuta `python -m http.server 8000`, luego entra a http://localhost:8000.
