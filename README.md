# CourseForge Starter (v2)
Clon simple del flujo de LearningStudioAI: Tema → Subtemas → Contenido → Publicar → Descargar (PDF/SCORM).

## Secrets requeridos (en Firebase Studio)
- GEMINI_API_KEY
- GCS_BUCKET  (ej: YOUR_PROJECT_ID.appspot.com)
- SHARE_BASE_URL  (ej: https://YOUR_PROJECT_ID.web.app/share)

## Pasos
1) Sube este repo a Firebase Studio o clónalo localmente.
2) Deploy Hosting + Functions.
3) Abre `/` → escribe un tema → Generar Outline → Editor → Generar contenido → Publicar → `/share/{id}` → Descargar PDF/SCORM.
