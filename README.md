# UNIGIS Partner Portal — GitHub Pages

Fecha: 2025-09-13

Este paquete contiene:
- `index.html`: tu portal listo para publicar.
- `.nojekyll`: desactiva el procesamiento de Jekyll en GitHub Pages (no obligatorio, pero recomendado).
- Este `README.md` con instrucciones.

---

## Publicar en GitHub Pages (5 pasos)

1. **Crea un repositorio nuevo** en GitHub (por ejemplo: `unigis-partner-portal`).  
   - Visita https://github.com/new → ponle nombre y hazlo **Public**.

2. **Sube estos archivos** al repositorio:  
   - `index.html`  
   - `.nojekyll`  
   - `README.md`

   Puedes arrastrar y soltar los archivos en la vista del repo → **Add file** → **Upload files** → **Commit changes**.

3. **Activa GitHub Pages**:  
   - En tu repo, ve a **Settings** → **Pages**.  
   - En **Build and deployment**, elige:  
     - **Source**: *Deploy from a branch*  
     - **Branch**: `main` / **root** (`/`)  
   - Guarda. GitHub generará una **URL pública** del tipo:  
     `https://<tu-usuario>.github.io/unigis-partner-portal/`

4. **Espera el deploy** (~1–2 min).  
   - Verás un badge verde **"Your site is live"** en **Settings → Pages**.  
   - Abre la URL y verifica que carga el portal.

5. **(Opcional) Dominio propio**  
   - En **Settings → Pages**, añade tu dominio y crea un archivo `CNAME` con el dominio.  
   - Configura los registros DNS (CNAME) en tu proveedor.  
   - Espera propagación de DNS.

---

## Incrustar en Canva (Embed)

1. Copia la **URL pública** de tu portal (por ejemplo, `https://<tu-usuario>.github.io/unigis-partner-portal/`).  
2. En tu diseño de **Canva**: **Apps** → **Integrar / Embed** → pega la URL.  
3. Ajusta el marco al tamaño deseado y **Publica** tu sitio de Canva.

> Nota: Canva no acepta HTML pegado directamente; requiere una **URL pública** o un **iframe**.

---

## Actualizar contenido

- Edita `index.html` localmente → súbelo al repo con un nuevo commit.  
- GitHub Pages redeployará automáticamente y la URL se actualizará (puede tardar 1–2 minutos).

---

## Soporte rápido

- Si no ves cambios, fuerza recarga (Ctrl/Cmd+Shift+R).  
- Revisa **Settings → Pages** por errores de build.  
- Asegúrate de que el repo es **Public** (GitHub Pages para usuarios Free requiere público).

¡Listo! Tu portal ya está preparado para compartirse y para incrustarlo en Canva.
