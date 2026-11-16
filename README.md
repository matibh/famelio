# Famelio

Ranking comunitario de popularidad: las personas proponen figuras públicas y la comunidad las vota.

## Estado actual

Primera maqueta frontend en HTML, CSS y JavaScript puro. No requiere build ni dependencias.

### Funcionalidades de la demo
- Ranking mundial y argentino.
- Filtros por categoría y búsqueda.
- Votación de demostración.
- Propuesta de nuevas personas.
- Persistencia local mediante `localStorage`.

> Importante: los votos y propuestas todavía se guardan únicamente en el navegador de cada visitante. No son votos globales ni están sincronizados entre dispositivos. Para producción hay que conectar una base de datos y aplicar controles antiabuso.

## Publicar con GitHub Pages

1. Abrir **Settings → Pages** en el repositorio.
2. En **Build and deployment**, elegir **Deploy from a branch**.
3. Seleccionar la rama **main** y la carpeta **/ (root)**.
4. Guardar. GitHub Pages publicará el sitio cuando termine el despliegue.

## Próximos pasos
- Definir reglas de nominación y moderación.
- Conectar una base de datos compartida.
- Implementar identidad de votante y límites antiabuso.
- Incorporar perfiles, histórico y rankings por período.
