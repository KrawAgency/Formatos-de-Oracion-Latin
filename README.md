# Oraciones para doña Josefina

Página sencilla para abrir y guardar en el celular los formatos de rezo en PDF.

## Contenido
- `index.html` — la página (botones grandes, uno por oración)
- `pdf/` — los formatos:
  - Santo Rosario (Rosarii Beatæ Mariæ Vírginis)
  - 100 Réquiem Aeternam
  - 3 Ave Marías pro Ánimis Purgatorii
  - 3 Ave Marías de la Llama de Amor
  - Oración a San Padre Pío de Pietrelcina

## Publicar
Settings → Pages → Branch: `main`, carpeta `/ (root)` → Save.
La página queda en `https://krawagency.github.io/Formatos-de-Oracion-Latin/`

## Agregar un formato nuevo
1. Sube el PDF a la carpeta `pdf/` (nombre sin acentos ni espacios).
2. En `index.html` copia una línea `<a class="oracion" ...>` y cambia el archivo y el título.
