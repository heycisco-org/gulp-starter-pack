# GULP starter pack
Настроенная GULP сборка для автоматизации вёрстки.

### Описание
- Возможность обработки pug. Импорты в HTML.  
Например: `@@include(header.html')` в файле index.html вставит содержимое хедера в HTML.
- Импорт CSS файлов, обработка Post CSS с множеством оптимизаций.  
Можно подключить Tailwind CSS за пару кликов.
- Обработка JS с помощью Webpack.  
По умолчанию jQuery не используется, но в модулях присутствует.
- Конвертация картинок в webp, сжатие, при необходимости создание копий других размеров.
- Конвертация шрифтов в woff и woff2. Автоподключение шрифтов в CSS. Создание иконочного шрифта.
- Создана начальная структура файлов/папок для быстрого старта нового проекта.

### Команды
- `npm run dev` — режим разработки с автообновлением браузера.
- `npm run build` — компиляция под продакшен.
- `npm run zip` — упаковка проекта в zip архив.
- `npm run ftp` — выгрузка проекта на FTP.
- `npm run icons` — создание иконочного шрифта.

### Установка
	git clone https://github.com/heycisco/gulp-starter-pack
	cd gulp-starter-pack
	npm install --global gulp-cli
	npm install
Отредактировать **gulp/config/ftp.js** для использования загрузки на FTP.

---

### [Подробное описание](https://starchenkov.pro/notes/gulp-pack/ "Читать у меня на сайте")

[Мой Telegram](https://telegram.me/starchenkov "Если что-то пошло не так")
