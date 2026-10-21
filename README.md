# Operación Chupachups

Cuenta atrás y recuento de chupachups por alumno. Los datos están en `datos.json` y se guardan en este repositorio, así que los cambios permanecen para todos.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo (por ejemplo `operacion-chupachups`) y sube `index.html` y `datos.json`.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
3. En un minuto la página estará en `https://TU-USUARIO.github.io/operacion-chupachups/`.

## Crear el token para editar (solo una vez)

1. GitHub → foto de perfil → **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
2. **Repository access:** *Only select repositories* → elige este repositorio.
3. **Permissions → Repository permissions → Contents: Read and write**.
4. Genera el token y cópialo (empieza por `github_pat_`).

## Editar los datos

1. Abre la página y pulsa **Modo profesor** (abajo del todo).
2. La primera vez, pega el token y pulsa **Recordar token**. Queda guardado solo en ese navegador.
3. Usa **+ / −** y cambia la fecha objetivo si hace falta.
4. Pulsa **Guardar cambios en GitHub**. Cada guardado queda como un commit en el historial.

Los alumnos ven la página en modo lectura. Sin el token nadie puede modificar los datos.

También puedes editar `datos.json` directamente desde la web de GitHub (icono del lápiz).

## Si usas un dominio propio

Rellena `OWNER` y `REPO` en el bloque `CONFIG` al principio del script de `index.html`.
