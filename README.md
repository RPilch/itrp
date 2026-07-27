# ITRP Consultores — web para GitHub Pages

Sitio estático multipágina configurado para el dominio personalizado `itrpconsultores.com`.

## Publicación
1. Extraer el ZIP.
2. Subir **el contenido de la carpeta `itrp-web`** a la raíz del repositorio.
3. En GitHub: **Settings → Pages**.
4. Seleccionar **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
5. En **Custom domain**, confirmar `itrpconsultores.com`.
6. Cuando GitHub confirme el DNS, activar **Enforce HTTPS**.

## DNS esperado en GoDaddy
- Cuatro registros `A` para `@` apuntando a:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Un registro `CNAME` para `www` apuntando a `TU-USUARIO.github.io`.

No modificar los registros MX, TXT, Autodiscover ni otros registros del correo.

## Páginas
- `index.html`
- `nosotros.html`
- `servicios.html`
- `experiencia.html`
- `colaboradores.html`
- `contacto.html`
