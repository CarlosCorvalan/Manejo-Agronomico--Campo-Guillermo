# Campamento Guillermo — Manejo Agronómico

Aplicación web de una sola página para llevar el stock de agroquímicos, el historial
de manejo agronómico (aplicaciones/labores) y una biblioteca de consulta con fotos
de malezas del Campamento Guillermo.

## Uso

Abrir `index.html` en cualquier navegador (Chrome, Edge, etc.). No requiere instalación
ni conexión a un servidor propio.

## Guardado de datos

- Si se abre **dentro de Claude.ai** (como Artifact), los datos quedan compartidos
  entre todos los que abran ese mismo enlace.
- Si se abre **suelta** (doble clic, GitHub Pages, Lynx, etc.), los datos se guardan
  en el `localStorage` de ese navegador puntual — quedan solo en ese dispositivo/navegador,
  no se sincronizan automáticamente con otros.

## Documentación

Ver el documento de respaldo (`Campamento_Guillermo_Documento_Respaldo.docx`) para el
detalle de arquitectura, modelo de datos y hoja de ruta hacia un esquema multiusuario
con login (tipo GestorLotes Campo).
