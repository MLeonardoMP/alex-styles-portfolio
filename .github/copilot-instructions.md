# Copilot instructions (Microsoft FrontEnd / Coursera)

## Contexto del repo
- Este workspace es **documentación** (no hay app ni build): 4 archivos Markdown con front matter YAML para las actividades del capstone.
- Archivos principales:
  - `actividad-1-writing-and-enhancing-css.md`
  - `actividad-2-generating-responsive-design.md`
  - `actividad-3-enhancing-ui-ux-design.md`
  - `capstone-instrucciones-generales.md`

## Prioridad: cambios mínimos (fácil de revisar)
- Mantén los cambios **lo más cortos posible**: evita reescrituras grandes y edita solo las líneas necesarias.
- Prefiere ajustes puntuales y consistencia; no “re-formatees” secciones completas si no es imprescindible.

## Fuente de verdad: CV
- Cuando necesites datos biográficos, experiencia, skills o logros, basarte en el contenido de: `C:\Users\USUARIO\OD\Documents\Repos\CV`.
- Si falta información en el CV, **pregunta** antes de inventar detalles.

## Front matter YAML (crítico)
- Cada archivo empieza con front matter entre `---` y `---`. **No lo elimines** ni cambies su estructura.
- Mantén las claves existentes y el tipo de dato:
  - `post_title`, `author1`, `post_slug`, `microsoft_alias`, `featured_image`, `ai_note`, `summary`, `post_date` (strings)
  - `categories`, `tags` (listas YAML)
- Si cambias el título o el enfoque, actualiza también:
  - `post_slug` en kebab-case (ej: `alex-styles-activity-2-generating-responsive-design`)
  - `summary` (1 frase) y `tags` relevantes
  - `post_date` con la fecha real de edición (formato `YYYY-MM-DD`)

## Convenciones de contenido
- El cuerpo combina español e inglés; **preserva el idioma existente por sección** (no “traducciones masivas” sin pedirlo).
- Respeta la estructura de headings usada:
  - Título H2 del tema y subsecciones `### Introduction`, `### Instructions`, y pasos `#### Step N`.
- No inventes requisitos del curso: limita cambios a lo que el documento ya indica.

## Enlaces y referencias
- Mantén y valida los enlaces relativos entre actividades en `capstone-instrucciones-generales.md`:
  - `./actividad-1-writing-and-enhancing-css.md`, `./actividad-2-generating-responsive-design.md`, `./actividad-3-enhancing-ui-ux-design.md`
- Si renombraras un archivo (evitarlo salvo que el usuario lo pida), actualiza todos los enlaces.

## Qué NO asumir
- No asumas que existen `index.html`, `styles.css` o un sitio publicado en este repo; los docs describen pasos, pero el código puede estar fuera del workspace.
- No añadas nuevas páginas/actividades ni secciones “extra” (ej. rúbricas adicionales, checklists nuevos) a menos que el usuario lo solicite.

## Ediciones típicas (hazlo así)
- Correcciones puntuales: ortografía, claridad y consistencia (sin cambiar el sentido).
- Ajustes de metadatos: mantener YAML válido y coherente con el contenido.
- Si agregas ejemplos, que sean breves y explícitamente “ejemplo”, sin presentarlos como requisitos del curso.
