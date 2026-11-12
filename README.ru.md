<p align="center">
  <a href="README.md">English</a> ·
  <b>Русский</b> ·
  <a href="README.es.md">Español</a> ·
  <a href="README.pt.md">Português</a> ·
  <a href="README.de.md">Deutsch</a> ·
  <a href="README.fr.md">Français</a> ·
  <a href="README.zh.md">中文</a> ·
  <a href="README.ja.md">日本語</a> ·
  <a href="README.ko.md">한국어</a>
</p>

<p align="center">
  <img src="screenshots/banner.jpg" alt="Grimsby Helper">
</p>

<p align="center">
  <b>Здоровье компьютера — с первого взгляда.</b><br>
  Что грузит компьютер, насколько он греется и сколько места можно освободить. Ничего не удаляется, пока вы не нажмёте кнопку.
</p>

<p align="center">
  <a href="https://github.com/maksimkhatskevich/grimsby-helper/releases/latest"><img src="https://img.shields.io/github/v/release/maksimkhatskevich/grimsby-helper?label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F&color=2FA6A0" alt="Version"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-2FA6A0" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/%D0%B1%D0%B5%D1%81%D0%BF%D0%BB%D0%B0%D1%82%D0%BD%D0%BE-%D0%B1%D0%B5%D0%B7%20%D1%80%D0%B5%D0%BA%D0%BB%D0%B0%D0%BC%D1%8B-111314" alt="Free">
  <a href="https://github.com/maksimkhatskevich/grimsby-helper/releases"><img src="https://img.shields.io/github/downloads/maksimkhatskevich/grimsby-helper/total?label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9&color=858A8D" alt="Downloads"></a>
</p>

<p align="center">
  <a href="https://github.com/maksimkhatskevich/grimsby-helper/releases/latest"><b>⬇ Скачать для Windows</b></a>
  &nbsp;·&nbsp;
  <a href="#возможности">Возможности</a>
  &nbsp;·&nbsp;
  <a href="#приватность">Приватность</a>
  &nbsp;·&nbsp;
  <a href="#обратная-связь">Обратная связь</a>
</p>

![Grimsby Helper](screenshots/ru/home.jpg)

---

## Зачем Grimsby Helper

Программы для ПК обычно либо показывают стену цифр, либо обещают «ускорить» Windows одной волшебной кнопкой. Ни то ни другое не говорит просто, всё ли в порядке.

**Grimsby Helper отвечает просто.** Главная говорит «Всё хорошо», «Стоит обратить внимание» или «Есть проблема», объясняет причину понятными словами и показывает, что сделать.

---

## Возможности

### 🩺 Состояние ПК с первого взгляда

Оценка с причинами и кнопкой, что сделать. Ниже — процессор, память, температура, свободное место, сколько можно освободить и время без перезагрузки.

### 📈 Процессы

Процессы и приложения с нагрузкой на процессор, память, диск, сеть и видеокарту; сортировка, поиск и группировка по приложениям. Понятные имена и значки, расположение файла и издатель. Графики процессора, памяти, дисков, сети и видеокарты. **«Завершить»** и **«Завершить дерево»** спрашивают подтверждение, системные процессы защищены.

### 🌡 Датчики и здоровье дисков

Температура процессора по ядрам, частоты и потребление, видеокарты, диски, вентиляторы, материнская плата и батарея — всё, что сообщает ваш ПК. Здоровье дисков: состояние, износ SSD, наработка. История за час, день, неделю или месяц хранится только на вашем компьютере. Если датчика нет, Helper так и пишет, а не показывает нули.

![Датчики](screenshots/ru/sensors.jpg)

### 🧹 Чистка, которая сначала показывает

Временные файлы, кэш браузеров, Корзина, миниатюры, остатки обновлений Windows, старые журналы и файлы сбоев. Вы видите всё найденное с размерами и понятными описаниями, отмечаете, что убрать, и видите, сколько освободится. Файлы уходят в Корзину везде, где это возможно; где нельзя — Helper пишет об этом до нажатия. Вкладки и пароли браузеров не трогаются, чистки реестра нет.

### 🚀 Автозагрузка

Что запускается с Windows: записи реестра, папки автозагрузки, задачи планировщика и службы сторонних программ. Отключение и включение обратно; показан издатель, записи Microsoft и драйверов защищены от случайных изменений.

### 💽 Место на дисках

Наглядная карта того, что занимает место, самые большие файлы и папки. Удаление только вручную, в Корзину и с подтверждением.

![Место на дисках](screenshots/ru/space.jpg)

### 🔔 Трей и предупреждения

При закрытии окна Helper может остаться в трее: в подсказке значка — температура и нагрузка. Предупреждения о перегреве, нехватке места и памяти и о диске, который теряет здоровье: одно событие — одно уведомление. Запуск вместе с Windows по умолчанию выключен.

### 🔐 Права администратора

Сама программа работает без прав администратора. Для чтения датчиков они нужны, поэтому маленький отдельный агент получает их один раз, с подтверждением Windows. Температуре ядер, вентиляторам и материнской плате нужен ещё драйвер датчиков: Helper скачивает его официальный установщик только по вашей кнопке, сверяет контрольную сумму и устанавливает с подтверждением Windows. Удалить его можно в настройках. Всё остальное работает и без него.

🌍 **9 языков:** русский, английский, испанский, португальский, немецкий, французский, китайский, японский и корейский — переключаются в настройках сразу.

Светлая тема — в один клик, кнопка с солнцем вверху.

![Светлая тема](screenshots/ru/home-light.jpg)

---

## Скачать и установить

1. Откройте страницу **[последней версии](https://github.com/maksimkhatskevich/grimsby-helper/releases/latest)** и скачайте установщик `.exe`.
2. Запустите его. Windows может показать синее окно «Система Windows защитила ваш компьютер» — это обычное предупреждение для программ без платного сертификата подписи. Нажмите **Подробнее → Выполнить в любом случае**.
3. Откройте Helper — главная сразу покажет состояние компьютера.

**Требования:** Windows 10 или 11 (64 бит).

---

## Приватность

Grimsby Helper работает на вашем компьютере. Сведения о компьютере никуда не отправляются. Без аккаунтов, рекламы и аналитики. В интернет программа выходит, только чтобы проверить обновления и, если вы нажмёте кнопку, скачать драйвер датчиков.

---

## Программы Grimsby

<table>
  <tr>
    <td align="center" width="20%"><a href="https://github.com/maksimkhatskevich/grimsby-releases/blob/main/README.ru.md"><img src="screenshots/family/player.png" width="56" alt=""><br><b>Grimsby Player</b></a><br><sub>Офлайн-плеер для скачанной музыки и клипов</sub></td>
    <td align="center" width="20%"><a href="https://github.com/maksimkhatskevich/grimsby-converter/blob/main/README.ru.md"><img src="screenshots/family/converter.png" width="56" alt=""><br><b>Grimsby Converter</b></a><br><sub>Видео, аудио, фото и документы — конвертация без интернета</sub></td>
    <td align="center" width="20%"><a href="https://github.com/maksimkhatskevich/grimsby-tagger/blob/main/README.ru.md"><img src="screenshots/family/tagger.png" width="56" alt=""><br><b>Grimsby Tagger</b></a><br><sub>Пакетный редактор тегов: альбомы, обложки, имена файлов</sub></td>
    <td align="center" width="20%"><a href="https://github.com/maksimkhatskevich/grimsby-prompter/blob/main/README.ru.md"><img src="screenshots/family/prompter.png" width="56" alt=""><br><b>Grimsby Prompter</b></a><br><sub>Простой телесуфлёр, который следует за голосом</sub></td>
    <td align="center" width="20%"><img src="screenshots/family/helper.png" width="56" alt=""><br><b>Grimsby Helper</b><br><img src="screenshots/family/here-ru.svg" alt=""></td>
  </tr>
</table>

---

## Обратная связь

Нашли ошибку, есть идея или просто хотите сказать спасибо? Пишите:

- ✉️ почта: **[grimsbyy@gmail.com](mailto:grimsbyy@gmail.com)**
- 🐞 ошибки и идеи: [Issues](https://github.com/maksimkhatskevich/grimsby-helper/issues)
- 📣 Telegram: [@itsgrimsby](https://t.me/itsgrimsby)

---

## Лицензии

Grimsby Helper использует компоненты с открытым кодом, в том числе Electron и React. Полный список с текстами лицензий — в файле `THIRD_PARTY_NOTICES.txt` в папке программы.

<p align="center"><sub>© 2026 Grimsby</sub></p>
