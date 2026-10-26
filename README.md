# Un pedacito bonito de cada día · J&A

## Publicación gratuita
1. En GitHub, crea un repositorio público llamado `un-pedacito-bonito`.
2. Sube **index.html, styles.css, app.js, mensajes.json, fotos.json** y la carpeta `fotos` (si la usas) a la raíz del repositorio. No es necesario subir `build.py`.
3. En el repositorio entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, `main` y `/ (root)`. Guarda.
5. GitHub Pages mostrará el enlace en esa misma sección cuando termine de publicar. El enlace se mantiene mientras conserves el repositorio y la configuración.

## Añadir fotos sin cambiar el enlace
1. Crea una carpeta llamada `fotos` en el repositorio y sube allí las imágenes (por ejemplo `fotos/nosotros.jpg`).
2. Edita `fotos.json` así:
```json
[
  {"archivo":"fotos/nosotros.jpg","descripcion":"Nuestra primera foto juntos ♡"},
  {"archivo":"fotos/alondra.jpg","descripcion":"Un día bonito"}
]
```
3. Guarda el cambio en GitHub. En unos minutos se actualizará la misma página.

## Editar mensajes
Abre `mensajes.json`, localiza el día y cambia solamente el texto de `title` o `text`, manteniendo las comillas y las comas. Guarda los cambios.

## Notas
- Los mensajes se desbloquean por fecha usando la zona horaria `America/Mexico_City` (Guanajuato).
- Esta es una web estática: los mensajes futuros se ocultan en la interfaz, pero **no están protegidos frente a alguien que inspeccione el código**.
- Los favoritos se guardan localmente en cada dispositivo/navegador, no se sincronizan.
- No subas fotografías privadas sin el consentimiento de quienes aparecen; el repositorio público permite acceder a ellas.
- La web requiere conexión para cargar fuentes de Google; si fallan se usan fuentes alternativas.
