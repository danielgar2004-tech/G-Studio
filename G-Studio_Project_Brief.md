# G-Studio — Project Brief & Technical Specification
**Portafolio Web Profesional de Servicios de Desarrollo Web**
Versión 1.0 · Daniel García · 2026

---

## 1. Descripción del Proyecto

G-Studio es el portafolio web oficial de Daniel García, desarrollador web freelance especializado en la creación de sitios web de alto impacto para empresas, profesionales independientes y eventos sociales. El sitio debe posicionarse como una vitrina de excelencia técnica y creatividad, capaz de convertir visitantes en clientes desde el primer scroll.

La identidad visual se construye sobre la paleta **Obsidian & Volt**: negro profundo (#0D0D0D), azul noche (#1A1A2E), amarillo eléctrico (#D4FF00), blanco hielo (#F5F5F5) y gris acero (#4A4A6A). El tono es audaz, moderno y de alta categoría.

El objetivo primario del sitio es la **generación de leads y contrataciones directas** mediante múltiples puntos de conversión estratégicamente distribuidos a lo largo de la experiencia de navegación.

---

## 2. Stack Tecnológico Recomendado

- **HTML5 semántico** con estructura accesible
- **CSS3 avanzado**: variables CSS, animaciones, scroll-triggered transitions
- **JavaScript vanilla** (sin dependencias pesadas)
- **Google Fonts**: tipografía moderna (sugerencia: Space Grotesk + Inter)
- **Netlify** para deploy (consistente con proyectos anteriores)
- **WhatsApp API** para CTAs de contacto directo
- **SEO técnico completo**: meta tags, Open Graph, Twitter Cards, robots.txt, sitemap

---

## 3. Arquitectura de Secciones

### 3.1 · HERO — Primera impresión de impacto
- Fondo oscuro (#0D0D0D) con video loop o animación de partículas en código
- Nombre de la marca "G-Studio" con tipografía bold de alto impacto
- Tagline corto y poderoso: *"Sitios web que generan resultados reales"*
- Dos CTAs primarios en amarillo eléctrico: **"Ver portafolio"** y **"Contratar ahora"**
- Animación de entrada (fade-in + slide-up) al cargar la página
- Indicador de scroll animado en la parte inferior

### 3.2 · ESTADÍSTICAS — Credibilidad con números
- Contadores animados que se activan al hacer scroll (Intersection Observer)
- Métricas sugeridas: proyectos completados, clientes satisfechos, años de experiencia, tiempo promedio de entrega
- Fondo con leve contraste (#1A1A2E) para separar visualmente la sección
- Íconos minimalistas acompañando cada número

### 3.3 · SERVICIOS — Lo que ofrece G-Studio
- Cards con hover effect (elevación + borde en amarillo)
- Servicios a mostrar:
  - Sitios web para negocios y ventas
  - Landing pages de alto impacto
  - Invitaciones digitales para bodas y eventos
  - Sitios para asesores inmobiliarios
  - SEO técnico y optimización
  - Mantenimiento y actualizaciones
- Cada card incluye ícono, nombre del servicio, descripción breve y precio base orientativo
- CTA individual en cada card: *"Solicitar este servicio"*

### 3.4 · PORTAFOLIO — Proyectos reales
- Grid de proyectos con filtros por categoría: Todos / Negocios / Bodas / Inmobiliario
- Cada proyecto incluye:
  - Captura o mockup del sitio
  - Nombre del cliente
  - Descripción breve del trabajo realizado
  - Tags de tecnologías usadas
  - Botón "Ver sitio en vivo" (abre en nueva pestaña)
- Efecto overlay al hover con el nombre del proyecto y botón de enlace
- Proyectos iniciales: Alejandra / Incrementa Group · Boda Daniel & Narumi

### 3.5 · PROCESO DE TRABAJO — Cómo trabajamos
- Timeline horizontal o stepper visual con 4-5 pasos:
  1. Consulta gratuita
  2. Propuesta y presupuesto
  3. Diseño y desarrollo
  4. Revisiones y ajustes
  5. Entrega y lanzamiento
- Íconos animados por paso
- Énfasis en la rapidez: *"Entrega en 7 a 14 días"*

### 3.6 · POR QUÉ ELEGIR G-STUDIO — Diferenciadores
- Grid de 4-6 bloques con ventajas competitivas:
  - Código limpio y optimizado
  - SEO incluido en todos los proyectos
  - Diseño 100% responsivo (mobile-first)
  - Comunicación directa con el desarrollador
  - Revisiones incluidas sin costo adicional
  - Soporte post-entrega
- Fondo oscuro con íconos en amarillo para alto contraste

### 3.7 · TESTIMONIOS — Prueba social
- Carousel o grid de testimonios reales de clientes
- Foto de perfil (o inicial del nombre), nombre, empresa/rol, y cita del testimonio
- Estrellas de valoración (5/5)
- Fondo ligeramente diferenciado para sección

### 3.8 · PRECIOS — Transparencia que convierte
- Tres planes claramente diferenciados:
  - **Básico** — Landing page simple
  - **Profesional** — Sitio multipage con SEO *(más popular)*
  - **Premium** — Proyecto personalizado completo
- Tabla de comparación con checkmarks
- Botón CTA en cada plan
- Nota: *"¿Necesitas algo diferente? Hablemos."* con enlace a WhatsApp

### 3.9 · FAQ — Preguntas frecuentes
- Acordeón expandible con preguntas clave:
  - ¿Cuánto tiempo tarda el desarrollo?
  - ¿Qué necesito para empezar?
  - ¿Incluye hosting y dominio?
  - ¿Puedo hacer cambios después?
  - ¿Qué pasa si no me gusta el diseño?
- Fondo neutro, tipografía clara

### 3.10 · CONTACTO — Conversión final
- Formulario con campos: nombre, correo, teléfono, tipo de proyecto, mensaje
- Envío directo por WhatsApp (como en el sitio de Alejandra)
- Datos de contacto visibles: correo, WhatsApp, redes sociales
- Mapa de ubicación (Google Maps embed) — Cajamarca, Perú
- Horario de atención
- CTA final de alto impacto: *"¿Listo para tener tu sitio web? Escríbeme ahora"*

### 3.11 · FOOTER
- Logo G-Studio
- Navegación rápida
- Redes sociales (LinkedIn, Instagram, WhatsApp)
- Frase de marca
- Copyright

---

## 4. Especificaciones Técnicas Detalladas

### SEO Técnico (extraído de tus proyectos)
```html
<meta name="description" content="...">
<meta name="keywords" content="...">
<meta property="og:title" content="...">
<meta property="og:description" content="...">
<meta property="og:image" content="...">
<meta property="og:locale" content="es_PE">
<meta name="twitter:card" content="summary_large_image">
<meta name="robots" content="index, follow">
<meta name="theme-color" content="#0D0D0D">
```

### Animaciones y Efectos
- **Scroll reveal**: elementos aparecen al entrar en viewport (Intersection Observer API)
- **Contadores animados**: números que suben desde 0 al hacer scroll
- **Hover effects en cards**: translate Y + border glow en amarillo
- **Cursor personalizado**: punto amarillo que sigue al mouse (opcional, impacto alto)
- **Smooth scroll**: navegación fluida entre secciones
- **Navbar sticky**: fija al hacer scroll con cambio de opacidad
- **Preloader**: pantalla de carga con logo G-Studio animado (opcional)

### Responsividad
- Mobile-first design (breakpoints: 320px, 768px, 1024px, 1440px)
- Menú hamburguesa en móvil con animación de apertura
- Imágenes con lazy loading nativo (`loading="lazy"`)
- Tipografía fluida con `clamp()`

### Performance
- Minificación de CSS y JS
- Imágenes en formato WebP
- Fuentes con `font-display: swap`
- Preconnect a Google Fonts

---

## 5. Paleta de Colores Oficial

| Nombre       | Hex       | Uso principal                          |
|--------------|-----------|----------------------------------------|
| Obsidian     | #0D0D0D   | Fondo principal, secciones oscuras     |
| Night Blue   | #1A1A2E   | Fondos alternativos, navbar            |
| Volt         | #D4FF00   | CTAs, acentos, hovers, estadísticas    |
| Ice White    | #F5F5F5   | Tipografía principal, fondos claros    |
| Steel Gray   | #4A4A6A   | Textos secundarios, bordes sutiles     |

---

## 6. Tipografía

| Rol             | Fuente          | Peso      |
|-----------------|-----------------|-----------|
| Títulos hero    | Space Grotesk   | 700-800   |
| Headings        | Space Grotesk   | 600       |
| Cuerpo de texto | Inter           | 400       |
| Labels / Tags   | Inter           | 500       |

---

## 7. Prompt Maestro para Claude

Usa el siguiente texto exacto al crear el proyecto en Claude:

---

> Crea un sitio web profesional de portafolio para **G-Studio**, el estudio de desarrollo web de Daniel García. El sitio debe ser de alta categoría, oscuro y moderno.
>
> **Paleta de colores:** fondo principal #0D0D0D, fondo secundario #1A1A2E, acento amarillo #D4FF00, texto blanco #F5F5F5, gris #4A4A6A.
>
> **Tipografías:** Space Grotesk para títulos, Inter para cuerpo. Importar desde Google Fonts.
>
> **Secciones a incluir en este orden:**
> 1. Hero con animación de partículas, tagline impactante y 2 CTAs en amarillo
> 2. Estadísticas con contadores animados (Intersection Observer)
> 3. Servicios en cards con hover effect y CTA individual
> 4. Portafolio con filtros por categoría y overlay al hover
> 5. Proceso de trabajo en stepper de 5 pasos
> 6. Diferenciadores en grid con íconos
> 7. Testimonios en carousel
> 8. Precios en 3 planes con tabla comparativa
> 9. FAQ en acordeón
> 10. Contacto con formulario que envía por WhatsApp, mapa embed y datos de contacto
> 11. Footer completo
>
> **Requisitos técnicos:**
> - HTML, CSS y JS en un solo archivo index.html
> - SEO técnico completo (meta tags, Open Graph, Twitter Cards)
> - 100% responsivo (mobile-first)
> - Navbar sticky con cambio de opacidad al hacer scroll
> - Smooth scroll en toda la navegación
> - Animaciones de entrada con Intersection Observer
> - Lazy loading en imágenes
> - Botones WhatsApp con prefill de texto
> - Sin dependencias externas (solo Google Fonts y Font Awesome vía CDN)
>
> Usa contenido realista de placeholder. El desarrollador es Daniel García, basado en Cajamarca, Perú. Su WhatsApp es +51 XXX XXX XXX. El nombre del estudio es G-Studio.

---

*Documento preparado por Claude para Daniel García · G-Studio · Mayo 2026*
