# PromptLab Educativo

**Autor:** Ing. Hugo Fernando Trejos S. - MSc  
**Créditos:** Diseñado y desarrollado por Ing. Hugo Fernando Trejos S. - MSc  
**Copyright:** © 2026 · Todos los derechos reservados

Aplicación web estática en español para generar prompts personalizados de siete recursos: presentaciones, ilustraciones, infografías, videos, podcasts, mapas conceptuales y mapas mentales.

## Uso local

Abre `index.html` en un navegador moderno. Conserva la carpeta `assets` junto al archivo para que la ilustración del encabezado cargue correctamente. No requiere instalación, servidor, cuenta ni API.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `README.md` y la carpeta `assets` a la raíz de la rama principal.
3. En **Settings > Pages**, selecciona **Deploy from a branch**, la rama principal y la carpeta `/ (root)`.
4. Guarda los cambios. GitHub mostrará la URL pública cuando finalice el despliegue.

## Publicar en Netlify

1. Descomprime el ZIP descargado.
2. En Netlify, crea un sitio mediante despliegue manual.
3. Arrastra la carpeta `promptlab-educativo` que contiene `index.html`.
4. Netlify proporcionará la URL pública del sitio.


## Diseño visual

La portada incorpora una ilustración original de dos personas colaborando frente a un portátil, alineada con el tema de creación de prompts educativos. Esta ilustración se encuentra en `assets/hero-ilustracion-promptlab.png`.

## Privacidad y límites

Los campos se procesan localmente en el navegador. No se guardan ni envían a servidores desde esta aplicación. Los botones «Usar en ChatGPT», «Usar en Gemini», «Usar en Copilot» y «Usar en NotebookLM» intentan copiar el prompt al portapapeles y abren el sitio oficial elegido en otra pestaña. El usuario debe pegar el texto: no existe envío automático a estas plataformas. NotebookLM está orientado a trabajar con fuentes: puede ser necesario crear un cuaderno y cargar documentos antes de pegar el prompt en su chat. El acceso puede requerir iniciar sesión en el servicio elegido. Si el navegador no permite la copia, usa «Copiar prompt» o selecciona manualmente el texto generado.

La aplicación construye prompts, no genera directamente archivos de PowerPoint, imágenes, videos ni audio. Para eso utiliza el prompt en una herramienta compatible. No se incluye integración con APIs de pago.

## Herramientas disponibles

- **ChatGPT:** https://chatgpt.com/
- **Gemini:** https://gemini.google.com/app
- **Microsoft Copilot:** https://copilot.microsoft.com/
- **Google NotebookLM (Gemini Notebook):** https://notebooklm.google.com/

Estos enlaces solo abren los servicios: PromptLab Educativo no lee cuentas, no se conecta a sus APIs y no comparte automáticamente los campos del formulario.

## Actualizar un repositorio ya publicado

1. Descarga la versión actualizada de `index.html`, `README.md` y la carpeta `assets`.
2. En GitHub, entra al repositorio `PromptLab-Educativo` y reemplaza esos archivos en la rama `main` (por ejemplo, usando **Add file > Upload files** y confirmando la sustitución).
3. Confirma con **Commit changes**. Si GitHub Pages ya está habilitado, la publicación se actualizará tras el despliegue.

## Personalización

Puedes cambiar nombre, colores, textos y plantillas editando `index.html`. El proyecto no necesita dependencias externas.
