# assets

Публичный хостинг картинок для постов Threads (Graph API `image_url` требует
публично доступную ссылку, файл с диска не принимает).

`threads/` - AI-сгенерированные референсы (Format C, см. aleks-brand
`docs/brand/cards-carousel-brandbook.md`) и карточки перед публикацией.

Ссылка на файл: `https://raw.githubusercontent.com/aleks-brand-org/assets/main/threads/<файл>`

`threads/opensource-review/` - архив медиа собственных постов рубрики «обзор
OpenSource-решений». Ссылки Instagram CDN в выгрузках подписанные и протухают за
несколько дней, поэтому датасет
(`channel-threads/outputs/opensource-review-posts-dataset-*.json`) ссылается на
эти файлы. Имя файла: `<дата>-<shortcode>-<root|contN>-<индекс>.<ext>`.
