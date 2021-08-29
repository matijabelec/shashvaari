# shashvaari

## How to add more Quotes?

All quotes are listed under `quotes/` directory. Pull this repository, add quote(s) to `{pageNumber}.json`:

```json
[
    {"id": 11, "title": "Zavrzlari", "label": "Malo je zavrzlamasto."},
    {"id": 12, "title": "Errorari", "label": "Baca error."},
    {"id": 13, "title": "Rođendari", "label": "Jel ti rođendan?"},
    {"id": 14, "title": "Planeari", "label": "Ajmo na planning"},
    {"id": 15, "title": "Petkari", "label": "Jel petak?"},
    {"id": 16, "title": "Zbunjari", "label": "Molim?"},
    {"id": 17, "title": "Instaliari", "label": "Instaliram ispočetka."}
]
```

Keep in mind that exactly 10 quotes must be in one json file (because of simple pagination).
After 10th quote is added to json file, create new one (with name `{numberOfLastPage + 1}.json` ) and keep adding new quotes inside it.

Also, after all quotes are added, update `configs/default.json` with correct number of quotes.
