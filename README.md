# Ideas Gráficas – ideasgraficas.eu

Статичен сайт (HTML/CSS/JS), без build стъпка.

## Структура
- `index.html` – начална страница + страница „Ресурси“ (`#resursi`)
- `css/style.css`, `js/main.js`, `img/logo-mark.png` (G+I лого, оцветява се с CSS маска)
- `favicon.png`, `robots.txt`, `sitemap.xml`, `404.html`
- `_headers` – защитни хедъри за Cloudflare Pages
- `CNAME` – за GitHub Pages

## Публикуване
**Cloudflare Pages:** свържи GitHub репото, build command – празно, output directory – `/`. После добави домейна `ideasgraficas.eu`.

**GitHub Pages:** качи файловете в репо, Settings → Pages → branch `main` / root.

## За довършване
- Реален телефон, адрес и текстове на клиенти/отзиви
- Форма за контакт: сега е само визуална – свържи я с Formspree/Cloudflare Worker
- Логото на клиентите и реални снимки на проектите
