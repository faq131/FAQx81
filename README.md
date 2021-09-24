# FAQx81

## Структура проекта
- `_layouts/default.html` - шаблон
- `_includes/toc.htm` - генератор оглавления
- `assets/css/style.scss` -  стили
- `_includes_/scripts.html` -  js
- `index.md` - контент FAQ'а в [маркдауне](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- `heatmapdata-internal-clicks.json` - статистика внутренних переходов
- `heatmapdata-external-clicks.json` - статистика внешних переходов
- `README.md` - сие ридми
- `_config.yml` - конфиг GithubPages

## Счетчики кликов по ссылкам
[Демо](https://daks01.github.io/FAQx81/?showClicks)

**внешние переходы:**
- [Яндекс.Метрика](https://metrika.yandex.ru/stat/links?group=day&period=year&id=51819752&stateHash=5c52cc5b995fb633e5cbc505)
- экспорт cтатистики в csv
- переименовать клонку 'Адрес' в 'url'
- переименовать клонку 'Просмотры' в 'value'
- конвертонуть в json https://www.csvjson.com/csv2json
- удалить первый объект
- обновить json `heatmapdata-external-clicks.json`

**внутрение:**
- [Яндекс.Метрика](https://metrica.yandex.com/stat/popular?period=year&id=51819752&stateHash=5c52cbe5c21f174034394045)
- экспорт cтатистики в csv
- переименовать клонку 'Адрес' в 'url'
- переименовать клонку 'Просмотры' в 'value'
- конвертонуть в json https://www.csvjson.com/csv2json
- удалить первый объект
- добавить в json-файл `heatmapdata-internal-clicks.json`