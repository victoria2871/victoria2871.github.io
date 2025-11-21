# victoria2871.github.io

Este repositorio contiene una página estática sencilla para la alumna Victoria Arrese.

**Archivos importantes**:
- `index.html`: página principal con el texto "HOLAAAAAAAA".

**Cómo "compilar" / ejecutar localmente**

Nota: este es un sitio estático — no requiere compilación. Opciones para ver la página:

- Abrir directamente en el navegador:

  ```bash
  xdg-open index.html
  ```

- Servidor local sencillo (recomendado para evitar problemas de CORS y rutas):

  ```bash
  cd /workspaces/victoria2871.github.io
  python3 -m http.server 8000
  # luego abrir http://localhost:8000 en el navegador
  ```

**Publicar en GitHub Pages**

Este repositorio está nombrado `victoria2871.github.io`, por lo que GitHub Pages servirá el contenido a partir de la rama `main` automáticamente. Pasos:

```bash
git add index.html README.md
git commit -m "Agregar sitio estático"
git push origin main
# Esperar unos minutos y abrir: https://victoria2871.github.io/
```

