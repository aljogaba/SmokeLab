# Publicar Smoke Lab en GitHub Pages

## A. Subir los cambios con GitHub Desktop

1. Abre GitHub Desktop.
2. Selecciona el repositorio `SmokeLab`.
3. Cuando aparezcan los cambios, revisa que se incluyan:

   - `protocols/index.html`
   - `protocols/prt-001-pulled-pork.html`
   - `protocols/prt-002-borrego-al-pastor.html`
   - `assets/css/main.css`
   - `assets/js/site.js`
   - `.nojekyll`

4. En **Summary** escribe:

   `Add PRT-002 borrego al pastor protocol`

5. Haz clic en **Commit to main**.
6. Haz clic en **Push origin**.

## B. Activar GitHub Pages

1. Abre el repositorio `SmokeLab` en GitHub.
2. Entra a **Settings**.
3. En el menú lateral, abre **Pages**.
4. En **Build and deployment**, selecciona:

   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`

5. Presiona **Save**.
6. Espera a que GitHub termine la publicación.

La dirección esperada, si el repositorio se llama exactamente `SmokeLab`, es:

`https://aljogaba.github.io/SmokeLab/`

## C. Actualizaciones posteriores

Para cualquier cambio futuro:

1. Guarda los archivos en Visual Studio Code.
2. Revisa localmente con Live Server.
3. Abre GitHub Desktop.
4. Escribe un resumen del cambio.
5. Haz **Commit to main**.
6. Haz **Push origin**.

GitHub Pages volverá a publicar automáticamente los archivos de la rama configurada.
