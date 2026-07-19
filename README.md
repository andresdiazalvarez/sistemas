# SISTEMAS

App estatica para crear informes tecnicos de sistemas PCI desde GitHub Pages.

## Funciones

- Informes numerados y guardados en el navegador.
- Informes guardados con opcion de abrir, rectificar y volver a grabar.
- Cabecera del informe en mayusculas.
- Campos editables de Nº revision y Revision, con valores por defecto `1 RT-2026` y `TRIMESTRAL`.
- Varios sistemas dentro del mismo informe, incluso varios del mismo tipo.
- Cuadro resumen con cliente, edificio, sistema y denominacion de todos los sistemas preparados.
- Sistemas:
  - Central de Deteccion de Incendios
  - Central de Extincion de Incendios
  - Extincion de Incendios
  - Grupo de Presion Contra Incendios
  - Redes Contra Incendios
- Apartados por sistema:
  - Antecedentes
  - Comprobaciones realizadas
  - Estado
  - Normativa relacionada
  - Conclusion
- Texto fijo reutilizable por sistema y apartado.
- Texto redactado por voz cuando el navegador lo permita.
- Carga de hasta 10 imagenes por sistema desde archivo o camara.
- Montaje del informe con anexo fotografico.
- Descarga en Word y PDF.
- Borrado de informes guardados o del informe actual.

## Publicacion

Subir todo el contenido de esta carpeta a la raiz del repositorio y activar GitHub Pages desde `Settings > Pages`.

## Nota

La app guarda los datos en el navegador del usuario mediante `localStorage`. No sube ficheros a ningun servidor.
