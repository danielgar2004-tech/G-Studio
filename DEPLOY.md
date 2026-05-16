# Despliegue en Vercel — G-Studio

Esta guía asume que el repositorio ya está subido a GitHub.

---

## Pasos para publicar en Vercel

1. Ingresa a **https://vercel.com** e inicia sesión con tu cuenta de GitHub.

2. En el panel principal, haz clic en **"Add New…" → "Project"**.

3. Vercel listará tus repositorios de GitHub. Busca el repositorio de G-Studio
   y pulsa **"Import"**.

4. En la pantalla de configuración del proyecto:
   - **Framework Preset:** selecciona **"Other"** (es un sitio estático, sin framework).
   - **Root Directory:** déjalo en la raíz (`./`), salvo que `index.html` esté
     dentro de una subcarpeta — en ese caso, indica esa carpeta.
   - **Build Command:** déjalo vacío.
   - **Output Directory:** déjalo vacío (Vercel sirve la raíz automáticamente).

5. Pulsa **"Deploy"**. El despliegue tarda menos de un minuto.

6. Al terminar, Vercel asigna una URL del tipo `https://nombre-proyecto.vercel.app`.
   El sitio ya está en vivo.

---

## Despliegues automáticos

Cada vez que hagas `git push` a la rama principal, Vercel reconstruye y publica
el sitio de forma automática. No necesitas repetir el proceso de importación.

---

## Dominio personalizado (opcional)

Si más adelante adquieres un dominio `.com` o `.pe`:

1. En el panel del proyecto, ve a **"Settings" → "Domains"**.
2. Escribe tu dominio y pulsa **"Add"**.
3. Vercel mostrará los registros DNS (tipo `A` o `CNAME`) que debes configurar
   en el panel de tu proveedor de dominio.
4. Una vez propagado el DNS, el certificado SSL se emite automáticamente.

---

## Verificación posterior al despliegue

Antes de compartir el enlace, conviene confirmar:

- La imagen Open Graph se muestra correctamente al pegar el enlace en WhatsApp
  o redes (puedes probarlo en `https://www.opengraph.xyz`).
- El `sitemap.xml` es accesible en `https://tu-sitio.vercel.app/sitemap.xml`.
- Todos los botones de WhatsApp abren el chat con el mensaje correcto.
- El sitio se ve correcto en móvil y escritorio.

---

## Indexación en Google (recomendado)

1. Registra el sitio en **Google Search Console** (`https://search.google.com/search-console`).
2. Verifica la propiedad mediante el método de etiqueta HTML o registro DNS.
3. Envía el `sitemap.xml` desde la sección **"Sitemaps"**.

---

*G-Studio · Daniel García · 2026*
