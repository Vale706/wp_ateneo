🕊️ Portal Web Ateneo Néstor Kirchner (Catamarca)

✅ https://ateneonestorkirchner.com/

<img width="1919" height="842" alt="image" src="https://github.com/user-attachments/assets/7142c7e8-1b53-48f5-8091-a2bc2e085222" />

Este repositorio contiene el desarrollo y la configuración del sitio web oficial del Ateneo Néstor Kirchner, un espacio dedicado a la cultura, la formación política y el encuentro comunitario en Catamarca.

El sitio ha sido diseñado no solo como una vidriera informativa, sino como un nodo receptor de un ecosistema de automatización inteligente.

🚀 Características del Proyecto
Diseño Responsivo: Optimizado para dispositivos móviles, facilitando el acceso a la agenda cultural desde cualquier lugar.

Sección de Noticias/Eventos: Automatizada mediante flujos de trabajo externos.

Integración API: Configuración de endpoints REST para la recepción de contenido multimedia y artículos.

🛠️ Stack Tecnológico
Core: WordPress 6.x

UI/UX: Elementor Page Builder (Diseño personalizado).

Fuentes de Datos: Google Forms & Google Sheets (vía automatización).

Motor de Contenidos: Integración con IA Local (Ollama) para la redacción automática de notas.

⚙️ Arquitectura de Automatización (n8n)
El sitio web actúa como el "destino final" de un pipeline de datos que:

Escucha nuevas entradas en un formulario de Google.

Procesa imágenes de Google Drive (transformando enlaces de visualización a binarios .jpg).

Utiliza Prompt Engineering sobre modelos LLM para transformar datos crudos en artículos periodísticos con tono profesional y cercano.

Publica automáticamente en la base de datos de WordPress vinculando la Imagen Destacada.

<img width="1600" height="566" alt="image" src="https://github.com/user-attachments/assets/1df49150-1938-4d0a-a53f-9369acc42b65" />


📁 Secciones Clave
Inicio: Grilla dinámica de las últimas actividades.

Cursos y Talleres: Sección gestionada para inscripciones.

Biblioteca Digital: Espacio de consulta de materiales de formación.

🔧 Notas de Implementación
Si sos desarrollador y querés conectar una nueva herramienta al sitio:

Endpoint Base: https://ateneonestorkirchner.com/wp-json/wp/v2/

Autenticación: Se requiere Application Password generada desde el panel de usuario.

Permalinks: Configurados en /post-name/ para optimización SEO.
