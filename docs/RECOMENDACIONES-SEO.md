# Recomendaciones SEO – Con Alma Tech (anitalmada.github.io)

Revisión centrada en el posicionamiento de los **servicios** (Servicios Web, Asesoría y Capacitación) y en mejoras técnicas y de contenido.

---

## 1. Mejoras ya implementadas en el código

- **Canonical URL** en todas las páginas para evitar contenido duplicado.
- **Open Graph y Twitter Cards** para mejor aspecto al compartir en redes.
- **Meta description** única por página (layout + front matter).
- **robots.txt** para indicar sitemap y permisos de rastreo.
- **Sitemap** para que los buscadores descubran todas las URLs.

---

## 2. Títulos y descripciones por página

### Home (index)
- **Título sugerido:** `Con Alma Tech | Soluciones tecnológicas y capacitación – Buenos Aires`
- **Descripción actual:** está bien; se puede alargar un poco incluyendo servicios:  
  *"Soluciones tecnológicas simples para problemas concretos. Mantenimiento web, rescate de sitios, asesoría y capacitación tecnológica. Buenos Aires, Argentina."*

### Servicios Web
- **Título actual:** `Servicios Web - Con Alma Tech` → Correcto. Opcional: añadir ubicación o palabra clave:  
  `Mantenimiento y rescate de sitios web | Con Alma Tech`
- **Descripción:** ya es clara y con palabras clave (rescate, optimización, mantenimiento, migración). Mantenerla.

### Asesoría y Capacitación
- **Título actual:** `Asesoría y Capacitación - Con Alma Tech` → Correcto. Opcional:  
  `Asesoría tecnológica y capacitación para equipos | Con Alma Tech`
- **Descripción:** ya incluye “auditoría tecnológica”, “capacitación estratégica”. Mantenerla.

### Blog (listado)
- Añadir en `blog.md` una **description** en el front matter, por ejemplo:  
  *"Artículos sobre tecnología, seguridad online, mantenimiento web y buenas prácticas digitales. Con Alma Tech."*

### Entradas del blog
- **Implementado:** Todas las entradas tienen **`description`** en el front matter y enlaces internos a [Servicios Web](/servicios-web/) o [Asesoría y Capacitación](/asesoria-capacitacion/) donde corresponde.

---

## 3. Palabras clave por servicio (para contenido y búsqueda)

Usar estas ideas en títulos, descripciones y párrafos introductorios (sin forzar):

**Servicios Web**
- Mantenimiento web, mantenimiento de sitios web, actualización de sitios web
- Rescate de sitios web, recuperación de sitios, migración de hosting
- Optimización de sitios web, seguridad web, backups, WordPress (si aplica)
- Soporte web, administración de hosting

**Asesoría y Capacitación**
- Asesoría tecnológica, consultoría tecnológica, auditoría tecnológica
- Capacitación en tecnología, capacitación para equipos, formación tecnológica
- Transferencia de conocimiento, decisiones tecnológicas informadas
- Talleres de tecnología, seguridad online, buenas prácticas digitales

Incluir también **“Buenos Aires”** o **“Argentina”** en alguna página (por ejemplo en home o en una sección “A quién está dirigido”) para búsquedas locales.

---

## 4. Estructura de contenido (H1, H2, H3)

- **Una sola H1** por página con el tema principal (ej. “Servicios Web”, “Asesoría y Capacitación”). Ya lo tenés bien.
- En **Servicios Web**, los planes (Esencial, Profesional, etc.) y “Rescate y Optimización” están bien como H2/H3. Mantener orden lógico.
- En **Asesoría y Capacitación**, los dos bloques de servicio están bien como H3. Opcional: un H2 tipo “Servicios de asesoría y capacitación” y dentro los H3.

---

## 5. Enlaces internos

- Desde la home ya enlazás a Servicios Web y Asesoría y Capacitación. Correcto.
- En las páginas de servicios, el enlace “Volver a Servicios” a `/#servicios` está bien.
- Recomendación: en el **blog**, en cada entrada, incluir al final 1–2 enlaces a servicios relacionados (ej. post sobre mantenimiento web → enlace a “Servicios Web”; post sobre seguridad o capacitación → “Asesoría y Capacitación”). Ayuda al SEO y a la conversión.

---

## 6. Imágenes

- **Logo:** `alt="Con Alma Tech"` o `alt="Con Alma Tech - Inicio"` (ya tenés un alt adecuado).
- **Imágenes de blog:** usar `alt` descriptivo (qué se ve o de qué trata el artículo), no solo el título del post.
- **Iconos decorativos:** si son solo decorativos, se pueden dejar con `alt=""` o `role="presentation"` para que lectores de pantalla los ignoren.

---

## 7. Sitemap y robots

- **sitemap.xml:** generado por el plugin `jekyll-sitemap` (añadido en `_config.yml`). La URL será `https://anitalmada.github.io/sitemap.xml`.
- **robots.txt:** creado en la raíz con `Sitemap:` y reglas básicas. Asegurate de que en producción el dominio final (si usás uno propio) esté bien en `url` de `_config.yml`.

---

## 8. Redes sociales y rich results

- Con **Open Graph y Twitter Cards** las páginas se ven mejor al compartir. Si más adelante querés una imagen específica por servicio, podés definir `image` en el front matter de cada página y usarla en `og:image`.
- Para **empresa local**, podés valorar después un JSON-LD de tipo `LocalBusiness` o `ProfessionalService` (nombre, dirección, teléfono, servicios). No es obligatorio para empezar.

---

## 9. Resumen de acciones recomendadas (con prioridad)

| Prioridad | Acción |
|-----------|--------|
| Alta | Canonical, OG, Twitter Cards, robots.txt, sitemap (implementados en el código). |
| Alta | Añadir `description` en `blog.md` y en cada post nuevo. |
| Media | Ajustar títulos de home/servicios con variantes sugeridas arriba. |
| Media | Incluir “Buenos Aires” o “Argentina” en home o en una sección. |
| Media | Enlaces desde entradas del blog hacia páginas de servicios. |
| Baja | Alt text más descriptivo en imágenes del blog. |
| Baja | JSON-LD de negocio local si querés potenciar búsqueda local. |

Si querés, en un siguiente paso se puede bajar esto a cambios concretos en cada archivo (por ejemplo, el texto exacto del `description` del blog y de 2–3 posts de ejemplo).
