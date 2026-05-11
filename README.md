# Синтия — методичка

Сайт с памяткой по работе с собакой Синтией. Собран на MkDocs Material, деплоится на GitHub Pages.

## Как обновить контент

1. Поправить файлы в `docs/`:
   - `docs/index.md` — главная (one-pager).
   - `docs/exercises.md` — подробные упражнения.
2. `git add . && git commit -m "правки" && git push`
3. Через 1–2 минуты сайт обновится автоматически (GitHub Actions).

С телефона можно редактировать напрямую через веб-интерфейс GitHub — он сам коммитит.

## Локальный предпросмотр

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install mkdocs-material
mkdocs serve
```

Открыть http://127.0.0.1:8000
