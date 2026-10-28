# Музичні альбоми. Лабораторна робота 4

Словник полів моделі альбому.

| name | Тип даних | Елемент керування | Обмеження |
|---|---|---|---|
| title | рядок | input text | required, minlength 1, maxlength 100 |
| artist | рядок | input text + datalist | required, maxlength 80 |
| albumCode | рядок | input text | required, pattern [A-Z]{3}-[0-9]{3} |
| genre | рядок (перелік) | select | required; rock, electronic, hip-hop, jazz |
| releaseYear | ціле число | input number | required, min 1900, max 2026, step 1 |
| trackCount | ціле число | input number | required, min 1, max 100, step 1 |
| keyTrack | рядок | input text | maxlength 100 |
| addedAt | дата | input date | min 2024-01-01, max 2027-12-31 |
| coverFile | файл | input file | accept .jpg, .jpeg, .png, .webp, .avif |
| description | рядок | textarea | maxlength 500 |
| isOriginal | так/ні | input checkbox | без обмежень |