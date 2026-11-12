# RemBottle · Sitio web

Esta carpeta contiene la versión lista para publicar en **GitHub Pages**.

## Archivos necesarios

- `index.html`: la página completa.
- `rembottle-favicon.png`: ícono de la pestaña.
- `qr-demo.png`: QR visual de demostración del checkout.

No hay backend ni credenciales en este sitio estático. El pago, cupón y QR son demostraciones visuales: para cobrar de verdad hay que integrar un proveedor de pagos y un servidor seguro.

## Publicar con GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `rembottle`.
2. Subir esta carpeta completa al repositorio.
3. En GitHub: **Settings → Pages**.
4. Elegir **Deploy from a branch**, rama `main` y carpeta `/(root)`.
5. Guardar. GitHub mostrará una URL similar a `https://TU-USUARIO.github.io/rembottle/`.

## Actualizar el sitio

Después de editar `index.html`, hacer un commit y subir los cambios a la rama `main`. GitHub Pages vuelve a publicar automáticamente.
