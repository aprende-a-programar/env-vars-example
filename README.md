# Variables de entorno locales/producción

Cuando invocamos a `npm run dev` antes de llegar al index pasamos por local.js y eso toma las env-vars locales. En producción evitamos cargar las variables del archivo .env porque este no debería agregarse al repositorio.

# Importante

En este ejemplo se incluye un archivo .env que debería ignorarse en el repo (usando el archivi .gitignore) o tener valores que puedan ser distribuidos sin problemas, como cuestas de prueba o valores locales.
