# Registro Powerlifting CFBVN

Aplicación web estática para registrar y consultar:

- Pruebas de repetición máxima (RM directo y estimado con fórmula de Epley).
- Matriz de mejores marcas por estudiante y ejercicio.
- Cargas de trabajo entre el 100% y el 55% del RM.
- Mediciones antropométricas longitudinales.
- IMC, grasa corporal en kg, factor de actividad y gasto calórico total.
- Fichas individuales de fuerza y composición corporal.
- Lista compartida de estudiantes.
- Respaldo JSON y exportación CSV compatible con Excel.

## Uso

Abre la aplicación publicada en GitHub Pages. Los datos se guardan en el navegador del dispositivo mediante almacenamiento local.

Para trasladar o proteger la información, utiliza **Estudiantes y respaldo → Descargar respaldo JSON**. El archivo puede importarse posteriormente en el mismo dispositivo o en otro equipo.

## Privacidad

El repositorio contiene únicamente el código de la aplicación. Los nombres, pruebas y mediciones que se ingresan no se publican en GitHub: permanecen en el navegador, salvo que el usuario descargue y comparta voluntariamente un respaldo.

## Publicación

El flujo incluido en `.github/workflows/pages.yml` publica automáticamente el contenido de la rama `main` mediante GitHub Pages.
