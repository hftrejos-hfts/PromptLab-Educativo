# PromptLab Educativo

**Autor:** Ing. Hugo Fernando Trejos S. - MSc  
**Créditos:** Diseñado y desarrollado por Ing. Hugo Fernando Trejos S. - MSc  
**Copyright:** © 2026 · Todos los derechos reservados

Aplicación web estática en español para generar prompts personalizados de siete recursos: presentaciones, ilustraciones, infografías, videos, podcasts, mapas conceptuales y mapas mentales.

## Uso local

Abre `index.html` en un navegador moderno. No requiere instalación, servidor, cuenta ni API.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y `README.md` a la raíz de la rama principal.
3. En **Settings > Pages**, selecciona **Deploy from a branch**, la rama principal y la carpeta `/ (root)`.
4. Guarda los cambios. GitHub mostrará la URL pública cuando finalice el despliegue.

## Publicar en Netlify

1. Descomprime el ZIP descargado.
2. En Netlify, crea un sitio mediante despliegue manual.
3. Arrastra la carpeta `promptlab-educativo` que contiene `index.html`.
4. Netlify proporcionará la URL pública del sitio.

## Privacidad y límites

Los campos se procesan localmente en el navegador. No se guardan ni envían a servidores desde esta aplicación. El botón «Usar en ChatGPT» abre ChatGPT en otra pestaña; por privacidad y compatibilidad, no transmite automáticamente el texto del prompt. Copia el prompt y pégalo allí.

La aplicación construye prompts, no genera directamente archivos de PowerPoint, imágenes, videos ni audio. Para eso utiliza el prompt en una herramienta compatible. No se incluye integración con APIs de pago.

## Personalización

Puedes cambiar nombre, colores, textos y plantillas editando `index.html`. El proyecto no necesita dependencias externas.
