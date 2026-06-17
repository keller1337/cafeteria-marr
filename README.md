# Brock's Burgers — Sitio web

Sitio web de una sola página para **Brock's Burgers**, hamburguesería de medallón en Mar del Plata. Hecho con HTML, CSS y JavaScript puro (sin frameworks). Incluye menú interactivo en acordeón, reseñas reales de Google y enlaces a Instagram y WhatsApp.

## Estructura del proyecto

```
.
├── index.html          → el sitio completo (HTML + CSS + JS en un solo archivo)
├── productos/          → fotos de los productos y logo
│   ├── logo.png
│   ├── cheese-simple.webp
│   ├── brocks-doble.webp
│   └── ... (33 imágenes en total)
├── README.md
└── .gitignore
```

> Solo se suben `index.html`, la carpeta `productos/`, este `README.md` y el `.gitignore`.
> Los archivos `imgi_*` son las imágenes crudas descargadas de fu.do y están excluidos por el `.gitignore`.

## Cómo verlo localmente

Abrí `index.html` con doble clic en cualquier navegador. No necesita servidor ni instalación.

## Publicar gratis con GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `brocks-burgers`).
2. Subí estos archivos (ver más abajo).
3. En el repo, andá a **Settings → Pages**.
4. En **Source** elegí la rama `main` y la carpeta `/ (root)`. Guardá.
5. En 1–2 minutos tu sitio queda online en `https://TU-USUARIO.github.io/brocks-burgers/`.

## Características del menú

- Categorías en acordeón: arranca abierta la primera y el resto colapsado.
- Se abre al pasar el mouse o tocar; solo una abierta a la vez.
- Chips superiores para saltar a cada categoría con scroll suave.
- Accesible (botones con `aria-expanded`) y respeta `prefers-reduced-motion`.
- Para editar productos y precios: buscá la constante `MENU` dentro de `index.html`.

## Datos del negocio

- Instagram: [@brocksburgers](https://www.instagram.com/brocksburgers/)
- Ubicación: Mar del Plata
- Pedidos: WhatsApp / Instagram

---
© Brock's Burgers. Todos los derechos reservados.
