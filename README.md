# Sistema de Linea del Tiempo Interactiva: Historia del Deporte Panameño

### ¿Qué problema resuelve el proyecto?
Las exhibiciones físicas de los museos, como los muros de líneas de tiempo, son estáticas y difíciles de actualizar conforme ocurren nuevos hitos deportivos. Este proyecto consiste en el desarrollo y la administración continua de un sistema de kioscos digitales táctiles que complementa la exhibición física. Permite a los visitantes explorar la historia del deporte panameño mediante una interfaz dinámica, bilingüe e intuitiva, asegurando que el contenido (como las medallas y actuaciones históricas recientes) nunca se quede estancado y pueda actualizarse remotamente.

### ¿Qué tecnologías y características implementaste?
*   **Desarrollo Frontend:** Interfaz de usuario (UI) responsiva optimizada para pantallas táctiles de gran formato.
*   **Accesibilidad y Navegación:** Sistema de inicio táctil ("Toca para iniciar") y selección de idioma dinámico (ESPAÑOL | ENGLISH).
*   **Estructura de Datos Dinámica:** Módulo de línea de tiempo interactiva que renderiza tarjetas de eventos por año (ej. "Actuación Histórica", "Oro Histórico" de 2025).
*   **Administración de Contenido:** Arquitectura que me permite actualizar, editar y cargar nuevas hazañas deportivas y galerías multimedia sin necesidad de modificar el código base de la aplicación.

### ¿Cómo se instala y ejecuta el proyecto?
1. Clonar el repositorio en el hardware del kiosco destino.
2. Ejecutar la aplicación en Modo Kiosco a pantalla completa para restringir la navegación del usuario únicamente a la interfaz del museo.
3. Para actualizar el contenido, ingresar al panel de administración (CMS) con credenciales de administrador para añadir nuevos años, tarjetas de eventos o modificar los textos en español e inglés.
4. Reiniciar el servicio de visualización para que la pantalla de inicio cargue los nuevos recursos multimedia.

### Evidencia del Sistema en Producción
<img width="900" height="1600" alt="WhatsApp Image 2026-10-05 at 1 51 03 PM (1)" src="https://github.com/user-attachments/assets/e7d6573f-8269-4029-957e-1a8a393b29b4" />
<img width="1600" height="900" alt="WhatsApp Image 2026-10-05 at 1 51 02 PM (3)" src="https://github.com/user-attachments/assets/3472c123-7f10-48c7-8434-ceed1dba135d" />
