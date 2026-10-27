# cv

Резюме Игоря Миргородского — статические страницы на GitHub Pages.

| Версия | Страница | PDF |
|---|---|---|
| DevOps | [vegameta.github.io/cv](https://vegameta.github.io/cv/) | [cv.pdf](https://vegameta.github.io/cv/cv.pdf) |
| Инженер-программист: Windows, Linux, локализация ПО | [vegameta.github.io/cv/axto](https://vegameta.github.io/cv/axto/) | [cv_axto.pdf](https://vegameta.github.io/cv/axto/cv_axto.pdf) |

Каждая страница — один HTML-файл без сборки и скриптов, в трёх режимах:

- **компьютер** — лист A4 по центру экрана;
- **телефон** (уже 840 px) — обычная страница во всю ширину, крупный шрифт;
- **печать** — ровно один лист A4; из неё же сделаны PDF.

PDF пересобирается из HTML в headless Chromium:

```sh
chrome --headless --no-pdf-header-footer --print-to-pdf=cv.pdf index.html
```
