# JUMANAR Cotizador

Herramienta interna de gestión del taller — cotizaciones, ventas, producción y contratistas.

## Deploy en Netlify (recomendado)

1. Sube este repositorio a GitHub.
2. En Netlify → "Add new site" → "Import an existing project" → elige tu repositorio.
3. Configuración de build:
   - **Base directory:** `.` (raíz)
   - **Build command:** *(dejar vacío)*
   - **Publish directory:** `.`
4. Haz clic en "Deploy site".

El archivo `netlify.toml` ya tiene toda la configuración necesaria.

## Deploy en GitHub Pages

1. Ve a tu repositorio en GitHub → Settings → Pages.
2. Source: "Deploy from a branch" → rama `main` → carpeta `/ (root)`.
3. Guarda. GitHub Pages publicará `index.html` automáticamente.

## Almacenamiento

Los datos se guardan en el **localStorage del navegador** de quien use la app.
Cada persona que abra la URL tendrá sus propios datos separados.

> ⚠ **Importante:** los datos son locales al navegador. Si alguien borra el caché
> o abre la app en otro navegador/dispositivo, no verá los mismos datos.
> Usa el botón **"Exportar datos"** dentro de la app para hacer respaldos en Excel.

## Acceso

La app no tiene autenticación — cualquier persona con la URL puede acceder.
Si necesitas restringir el acceso, Netlify permite agregar contraseña básica en el plan Pro,
o puedes usar Netlify Identity para un login más robusto.

---

JUMANAR · "Se vuelve parte de tu hogar."
