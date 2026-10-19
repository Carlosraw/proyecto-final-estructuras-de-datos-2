# Plataforma de estructuras de datos

Proyecto final de Estructuras de Datos II (Universidad Autónoma de Occidente).

Plataforma web con pila, cola, buscador (trie y heap) y grafo. Los datos se guardan en una base de datos Supabase.

## Enlaces

- Sitio publicado: https://proyecto-final-uao.netlify.app
- Documentación: [documentacion-proyecto-final.pdf](documentacion-proyecto-final.pdf)
- Retos del curso: https://github.com/Carlosraw/estructuras-de-datos-2

## Integrantes

| Integrante | Código | GitHub | Contribución |
| --- | --- | --- | --- |
| Carlos Andrés Aristizábal Hernández | 2230750 | [@Carlosraw](https://github.com/Carlosraw) | Proyecto completo (trabajo individual) |

## Servicios

| Servicio | Uso | Enlace |
| --- | --- | --- |
| Netlify | Publicación del frontend | https://proyecto-final-uao.netlify.app |
| Supabase | Base de datos y API | https://tvgylkaychoetemcfhju.supabase.co |

## Ramas

| Rama | Contenido |
| --- | --- |
| main | Versión final, la que se despliega |
| feature/proyecto-final | Desarrollo del proyecto |

## Ejecutar en local

    npm install
    npm run dev

Se necesita un archivo `.env` en la raíz con `VITE_SUPABASE_URL` y `VITE_SUPABASE_ANON_KEY`.
