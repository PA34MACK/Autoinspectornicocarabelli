CARPETA DE BACKUPS

Esta carpeta almacena los respaldos exportados desde el dashboard.

Formato recomendado:

backup-AAAA-MM-DD_HH-MM.json

Ejemplo:

backup-2026-06-27_15-30.json

Procedimiento:

1. Exportar Backup desde el dashboard.
2. Guardar el archivo JSON en esta carpeta.
3. Ejecutar:

git add .
git commit -m "Backup 2026-06-27"
git push

Con esto todos los backups quedan almacenados en GitHub.
