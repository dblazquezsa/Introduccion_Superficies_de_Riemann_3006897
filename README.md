# Introducción a las Superficies de Riemann — 3006897

Material interactivo para el curso *Introducción a las Superficies de Riemann* (código 3006897), Departamento de Matemáticas, Facultad de Ciencias, Universidad Nacional de Colombia.

**Sitio del curso:** https://dblazquezsa.github.io/Introduccion_Superficies_de_Riemann_3006897/

## Contenido interactivo

| Unidad | Applet | Enlace |
|---|---|---|
| 1. Plano complejo extendido y transformaciones de Möbius | Transformaciones de Möbius sobre la esfera de Riemann | [Abrir](mobius-riemann-sphere.html) |
| 2. Funciones elípticas | — | próximamente |
| 3. Continuación meromorfa y superficies de Riemann | — | próximamente |
| 4. Superficies de Riemann abstractas | — | próximamente |

## Cómo está organizado

- `index.html` — portada del sitio; lista todos los applets agrupados por unidad del curso.
- `*.html` — cada applet es un archivo HTML independiente y autocontenido (sin dependencias externas ni build), que se puede abrir localmente con doble clic o servirse tal cual desde GitHub Pages.
- El sitio se publica automáticamente con **GitHub Pages** a partir de la rama `main`, carpeta raíz.

## Añadir un nuevo applet

1. Sube el nuevo archivo `.html` a este repositorio: botón **Add file → Upload files** en la página principal del repositorio.
2. Añade una tarjeta en `index.html`, dentro de la sección de la unidad correspondiente. El bloque tiene esta forma (puedes copiar y adaptar uno ya existente, o pedir ayuda para generarlo):

   ```html
   <a class="card" href="nombre-del-nuevo-archivo.html">
     <span class="card-tag">Disponible</span>
     <h3>Título del applet</h3>
     <p>Descripción breve de qué explora y cómo se usa.</p>
     <span class="open">Abrir el applet →</span>
   </a>
   ```

   Esto reemplaza la tarjeta `placeholder` ("Próximamente") de esa unidad.
3. Espera 1–2 minutos a que GitHub Pages vuelva a publicar el sitio; el cambio aparece automáticamente en la misma URL.

## Uso

Material de apoyo para los estudiantes del curso 3006897. Los applets no requieren instalación ni cuenta: basta con abrir el enlace en cualquier navegador, incluido el del celular.
