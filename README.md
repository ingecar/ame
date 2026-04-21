# ame
prueba 2026

## Sobre el Proyecto

Esta es una aplicación web, lo que implica las siguientes características y alcances fundamentales:

*   **Accesibilidad Universal:** Los usuarios pueden acceder a la plataforma desde cualquier dispositivo (computadora de escritorio, tablet o teléfono móvil) únicamente utilizando un navegador web moderno y una conexión a internet, sin necesidad de descargar o instalar software adicional.
*   **Arquitectura Cliente-Servidor:**
    *   **Frontend (Cliente):** Proveerá una interfaz de usuario intuitiva, dinámica y completamente responsiva, garantizando una experiencia de usuario (UX) óptima sin importar el tamaño de la pantalla.
    *   **Backend (Servidor):** Se encargará de gestionar la lógica de negocio, procesar los datos de manera eficiente y asegurar la persistencia y gestión de la información en una base de datos.
*   **Mantenimiento y Actualizaciones Centralizados:** Al ser una aplicación web, todas las actualizaciones, correcciones de errores y nuevas funcionalidades se implementan directamente en el servidor. Esto significa que todos los usuarios tendrán acceso instantáneo a la última versión del sistema sin requerir ninguna acción por su parte.
*   **Seguridad:** Se implementarán prácticas de seguridad estándar de la industria (como el uso de protocolos cifrados HTTPS) para proteger la integridad y privacidad de la transmisión de datos entre los usuarios y el servidor.

## Guía de Contribución y Buenas Prácticas

Para mantener la calidad y el orden del código en el proyecto **ame**, seguimos un conjunto de buenas prácticas de control de versiones:

1. **Mensajes de Commit con Significado (Conventional Commits):**
   Todos los commits deben seguir la estructura de *Conventional Commits*: `<tipo>[alcance opcional]: <descripción>`.
   - Ejemplos de tipos: `feat` (nueva característica), `fix` (corrección), `docs` (documentación), `style` (formato), `refactor` (reestructuración del código), `test` (pruebas).
   - Ejemplo de mensaje: `feat(ui): agregar botón de inicio de sesión`

2. **Versionado Semántico (SemVer):**
   Se versiona el proyecto siguiendo el estándar [SemVer 2.0.0](https://semver.org/). Las versiones siguen el formato `vMayor.Menor.Parche`.

3. **Bitácora de Cambios:**
   Los cambios de cada versión se registran en el archivo `CHANGELOG.md`.

4. **Flujo de Trabajo (GitHub Flow):**
   Utilizamos el modelo **GitHub Flow**:
   - La rama `main` (o `master`) siempre es desplegable.
   - Todo desarrollo de nuevas funcionalidades o correcciones se realiza en ramas temporales (`feature-branches` o `hotfixes`).
   - Se integran los cambios mediante *Pull Requests* para revisión de código antes de hacer el merge hacia la rama principal.

5. **Versionar todos los artefactos:** Todo elemento relacionado al proyecto (código, documentación, scripts de base de datos) debe ser versionado.

6. **Commits de un solo propósito:** Cada commit debe tener una única responsabilidad (ej: no mezclar el arreglo de un bug y una nueva funcionalidad en el mismo commit).
