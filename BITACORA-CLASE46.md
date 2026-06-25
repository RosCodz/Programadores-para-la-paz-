# Bitácora Clase 46

## Datos

Nombre: Luis Arrieta
Fecha: 25 junio 2026
Clase: 46
Rama GitHub: clase-46-scrumban-clickup-arquitectura

## Comunicaciones

¿Qué es Scrumban?
Scrumban es una metodología que combina Scrum y Kanban para organizar el trabajo
por metas e historias, visualizando el avance mediante columnas y tarjetas.

¿Qué es backlog?
Es la lista ordenada de todas las tareas e historias de usuario que se deben
desarrollar en el proyecto, priorizadas según su importancia.
¿Qué es una historia de usuario?
Es una descripción corta de una funcionalidad escrita desde la perspectiva
del usuario, con el formato: Como [tipo de usuario], quiero [funcionalidad],
para [beneficio].

¿Qué tarjeta se movió en ClickUp?
HU-01 - Configurar tablero Scrumban del proyecto, movida a "En desarrollo".

## Jurídico

¿Cuál es el alcance legal del sistema?
La plataforma genera borradores y orientaciones de apoyo pedagógico.
No reemplaza asesoría jurídica ni radica documentos automáticamente.

¿Qué datos no se deben usar en clase?
Datos personales reales, documentos reales de ciudadanos, tokens,
claves, credenciales o archivos .env con información sensible.

¿Por qué el sistema no reemplaza revisión jurídica?
Porque genera borradores que deben ser revisados por un profesional
antes de usarse en un trámite real.

## Tecnología

¿Qué carpetas se crearon?
src/routes, src/services, src/middleware, src/data, public/css,
public/js, docs, uploads, logs, tmp.

¿Qué archivo protege secretos?
El archivo .gitignore, que evita que .env, node_modules, uploads,
logs y archivos temporales se suban al repositorio.

¿Qué ruta se probó?
La ruta GET /estado en http://localhost:3000/estado

¿Qué respondió /estado?
Respondió un JSON con estado "activo", nombre de la app, entorno
"development", módulo 5, semana 10, clase 46 y mensaje de confirmación.

## Evidencia

Estado final de HU-01 en ClickUp: En desarrollo
Commit realizado: Clase 46 crea base del proyecto y tablero Scrumban
Observaciones: Estructura base del proyecto creada correctamente.