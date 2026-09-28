# mIND+ · Landing

Esta carpeta funciona en cualquier hosting estático gratuito: **Cloudflare Pages** (recomendado), **Netlify**, **Vercel** o **GitHub Pages**. No necesita servidor propio.

## 1 · Publicar el sitio

**Cloudflare Pages (recomendado):**
1. Cree una cuenta gratis en pages.cloudflare.com.
2. "Create a project" → "Upload assets" → arrastre esta carpeta completa.
3. Listo. Le da un enlace `algo.pages.dev` al instante, sin límite de "créditos" para un sitio estático.

**Netlify:** arrastre esta carpeta en app.netlify.com/drop, igual que antes.

## 2 · Recibir las solicitudes de prueba gratuita (Formspree, gratis)

El formulario ya está conectado a Formspree, solo falta activarlo:

1. Cree una cuenta gratis en **formspree.io** con el correo **jimenezdavidandres@gmail.com** (o el que prefiera para recibir las solicitudes).
2. Cree un formulario nuevo (New Form). Formspree le da una URL como:
   `https://formspree.io/f/xxxxxxxx`
3. Abra `index.html` de esta carpeta, busque el texto **`TU_ID_AQUI`** (línea con `const CONFIG`) y reemplace toda esa dirección por la que le dio Formspree.
4. Guarde y vuelva a subir la carpeta (arrastrar de nuevo).
5. Confirme su correo en Formspree la primera vez que llegue una solicitud de prueba: se lo pedirán por correo.

Con el plan gratuito de Formspree caben 50 solicitudes al mes, más que suficiente para agendar demostraciones.

Si en algún momento prefiere no usar Formspree, el botón "Copiar resumen" y el enlace de WhatsApp del formulario siguen funcionando sin ninguna configuración.

## 3 · Número de WhatsApp del equipo de ventas (opcional)

En la misma línea `const CONFIG`, complete `WHATSAPP` con el número con indicativo, sin + ni espacios (ejemplo: `573001234567`). Así aparece un botón para enviar la solicitud por WhatsApp además del correo.

## Aviso

Las vistas de la plataforma en este sitio son ilustrativas: sin nombre de conjunto, dirección ni valores reales.
