# Pullside: Gestor de Prompts Reutilizables para IA

## Descripción del Proyecto

**Pullside** es una aplicación web ligera y completamente del lado del cliente diseñada para gestionar y organizar tus prompts (instrucciones) reutilizables para modelos de Inteligencia Artificial. Permite a los usuarios crear, editar, eliminar y almacenar sus prompts de forma sencilla, facilitando su acceso y copia al portapapeles para un uso rápido en diversas plataformas de IA.

Ideal para desarrolladores, investigadores o cualquier persona que trabaje frecuentemente con prompts de IA y necesite una herramienta eficiente para su gestión.

## Características Principales

✨ **Gestión Completa de Prompts (CRUD):**
*   **Crear:** Añade nuevos prompts con un nombre descriptivo y su contenido.
*   **Editar:** Modifica el nombre o el contenido de cualquier prompt existente.
*   **Eliminar:** Borra prompts que ya no necesites (con confirmación).
*   **Visualizar:** Explora tus prompts en una interfaz de cuadrícula intuitiva.

📋 **Copia Rápida al Portapapeles:**
*   Un solo clic en cualquier tarjeta de prompt copia automáticamente su contenido al portapapeles, listo para ser pegado.

💾 **Persistencia y Portabilidad de Datos:**
*   **Guardar Configuración:** Exporta todos tus prompts a un archivo JSON (`.json`) para respaldo o para compartir.
*   **Cargar Configuración:** Importa prompts desde un archivo JSON, reemplazando los prompts actuales.
*   **Añadir Configuración (Merge):** Fusiona prompts de un archivo JSON con los existentes, añadiendo solo los nuevos y evitando duplicados.

🚀 **Interfaz de Usuario Intuitiva:**
*   Diseño minimalista y responsive, adaptado a diferentes tamaños de pantalla.
*   Modales para la creación y edición de prompts.
*   Notificaciones "toast" para feedback instantáneo al usuario.
*   Estado vacío amigable para nuevos usuarios.

## Tecnologías Utilizadas

*   **HTML5:** Para la estructura fundamental de la aplicación.
*   **CSS3:** Estilos personalizados para un diseño moderno, limpio y responsive.
*   **JavaScript (Vanilla JS):** Toda la lógica de la aplicación, incluyendo la gestión de datos, la interacción con la UI y la persistencia local.

## Cómo Usar

Pullside es una aplicación web de un solo archivo, lo que la hace extremadamente fácil de usar:

1.  **Descargar el archivo:** Descarga el archivo `Pullside.html` a tu ordenador.
2.  **Abrir en el navegador:** Simplemente abre el archivo `Pullside.html` con tu navegador web preferido (Chrome, Firefox, Edge, etc.).

¡Y listo! La aplicación se ejecutará directamente en tu navegador.

### Funcionalidades en la Interfaz:

*   **`+ Nuevo`:** Abre un modal para crear un nuevo prompt.
*   **`📂 Cargar`:** Carga un archivo `.json` de configuración de prompts, reemplazando los actuales.
*   **`📥 Añadir`:** Carga un archivo `.json` de configuración de prompts, fusionándolos con los actuales (añade nuevos, mantiene existentes).
*   **`💾 Guardar`:** Guarda la configuración actual de prompts en un archivo `.json`.
*   **`✏️` (Editar)::** Edita un prompt existente.
*   **`🗑️` (Eliminar):** Elimina un prompt existente.
*   **Clic en tarjeta de prompt:** Copia el contenido del prompt al portapapeles.

## Despliegue (GitHub Pages)

Dado que Pullside es una aplicación de un solo archivo HTML/CSS/JS, es ideal para ser desplegada en GitHub Pages.

1.  **Sube el archivo `Pullside.html`** a la raíz de tu repositorio de GitHub.
2.  **Configura GitHub Pages:**
    *   Ve a la pestaña **"Settings"** de tu repositorio en GitHub.
    *   Haz clic en **"Pages"** en el menú lateral.
    *   En la sección **"Build and deployment"**, selecciona **"Deploy from a branch"**.
    *   En la sección **"Branch"**, selecciona la rama **`main`** (o la rama donde subiste el archivo) y la carpeta **`/ (root)`**.
    *   Haz clic en **"Save"**.

Tu aplicación estará disponible en una URL similar a `https://[tu-usuario].github.io/[nombre-del-repositorio]/`.

## Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar Pullside, no dudes en abrir un issue o enviar un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` (si existe) para más detalles.

## Autor

Raúl García-Calzada

---

**Nota:** Este `README.md` asume que el archivo `Pullside.html` es el único archivo principal del proyecto y que no hay otros archivos de código fuente o directorios complejos.
