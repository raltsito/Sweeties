# Sweeties Bubba Teas & More — demo

Sitio demo autocontenido (una sola página, todo embebido). No requiere build ni dependencias.

## Desplegar en Vercel

**Opción rápida (drag & drop):**
1. Entra a https://vercel.com/new
2. Arrastra esta carpeta `deploy/` completa.
3. Deploy. Listo — Vercel sirve `index.html` en la raíz automáticamente.

**Con CLI:**
```bash
cd deploy
npx vercel --prod
```

**Desde GitHub:** sube esta carpeta a un repo y conéctalo en Vercel. No hay que configurar framework (es un sitio estático) ni comando de build.

## Notas
- El carrito, filtros y selector Pickup/Delivery funcionan del lado del cliente (demo, sin pagos).
- El botón de WhatsApp y "Contáctanos" abren un chat al 844 448 2262.
- Para cambiar textos, precios o fotos, edita el archivo fuente `.dc.html` del proyecto y vuelve a exportar.
