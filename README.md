title: services-quick-page
sdk: static
colorFrom: blue
---
# services-quick-page

Una landing page estática que muestra los servicios de una empresa y permite contactar vía WhatsApp con un solo clic.

## Estructura de archivos

- **index.html** – Página única, contiene todo el HTML, CSS y JavaScript necesario.
- **config.json** – Archivo de configuración opcional para personalizar título, colores y lista de servicios sin tocar el código.
- **README.md** – Este documento.

## Características

- **Carga rápida**: animación de 1 s que simula “creación en 1 minuto”.
- **Responsive mobile‑first** con un solo contenedor de ancho máximo 900 px.
- **Botón flotante de WhatsApp** y botón en el header, generados dinámicamente a partir de `config.json`.
- **Fade‑in** de las tarjetas de servicios al hacer scroll (IntersectionObserver).
- **SEO**: meta tags, Open Graph y JSON‑LD.
- **Accesibilidad**: foco visible, respeta `prefers-reduced-motion`.
- **Sin dependencias de build**: solo HTML, CSS y JavaScript puro.

## Uso

1. Copia los archivos al directorio raíz de tu servidor estático.
2. (Opcional) Edita `config.json` para cambiar el título, el color primario y la lista de servicios.
3. Abre `index.html` en el navegador. La página se mostrará automáticamente.

## Licencia

MIT – libre para reutilizar y modificar.