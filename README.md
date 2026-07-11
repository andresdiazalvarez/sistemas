# Informe correctivo

App web estatica para GitHub Pages.

## Que hace

- Carga varios informes PDF.
- Une todos los PDFs en un unico archivo descargable.
- Permite pegar un texto con criterios de formato y redaccion.
- Permite cargar o pegar un modelo de apoyo.
- Genera una vista previa de informe correctivo.
- Descarga el informe generado en PDF.
- Permite volver a la pantalla principal y eliminar los PDFs cargados.

## Publicacion en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube estos archivos a la raiz del repositorio.
3. En GitHub, entra en Settings > Pages.
4. En Source, elige Deploy from a branch.
5. Selecciona la rama main y la carpeta root.
6. Guarda los cambios.

GitHub generara una URL publica para abrir la app.

## Nota importante

La app funciona directamente en el navegador. No necesita servidor propio.

La lectura de PDFs depende de que el PDF tenga texto seleccionable. Si el PDF es un escaneo sin OCR, se podra unir y descargar, pero el analisis del contenido sera limitado.
