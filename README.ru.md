<p align="center">
  <a href="README.md">English</a> · <b>Русский</b>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/hero-ru-dark.png">
    <img src=".github/readme/hero-ru-light.png" width="880" alt="StashTrash — личное хранилище на собственном сервере">
  </picture>
</p>

<p align="center">
  <a href="https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-android-arm64-v8a.apk"><img src=".github/readme/button-android.png" width="168" alt="Скачать для Android"></a>
  <a href="https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-macos.dmg"><img src=".github/readme/button-macos.png" width="168" alt="Скачать для macOS"></a>
  <a href="https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-windows-x64.zip"><img src=".github/readme/button-windows.png" width="168" alt="Скачать для Windows"></a>
  <a href="https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-linux-x64.tar.gz"><img src=".github/readme/button-linux.png" width="168" alt="Скачать для Linux"></a>
  <picture><source media="(prefers-color-scheme: dark)" srcset=".github/readme/button-ios-soon-ru-dark.png"><img src=".github/readme/button-ios-soon-ru-light.png" width="168" alt="iOS: скоро"></picture>
</p>

<p align="center">
  <a href="https://github.com/Salesao/stashtrash/releases/latest"><img src="https://img.shields.io/github/v/release/Salesao/stashtrash?style=flat-square&color=0161fc&label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F" alt="Последняя версия"></a>
  <a href="https://github.com/Salesao/stashtrash/releases"><img src="https://img.shields.io/github/downloads/Salesao/stashtrash/total?style=flat-square&color=0161fc&label=%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B8" alt="Загрузки"></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/showcase-dark.png">
    <img src=".github/readme/showcase-light.png" width="880" alt="StashTrash на компьютере и телефоне: общая лента с заметками, ссылками, документами, фото и голосовыми">
  </picture>
</p>

## Что это

StashTrash — это «Избранное» из мессенджера, только на вашем собственном сервере. Вы отправляете себе заметку, ссылку, фото, документ, видео, музыку или голосовое, и оно появляется на всех ваших устройствах: на телефоне, ноутбуке и рабочем компьютере.

Файлы и база лежат на вашем сервере. Настраивать его вручную не нужно: приложение подключается к нему по SSH и ставит всё само.

## Зачем

- **Ваши данные — у вас.** Сервер ваш, и правила хранения тоже ваши. Объём ограничен только диском сервера.
- **Одно место для всего, что жалко потерять.** Больше не нужно писать самому себе в мессенджере, вести заметки отдельно, держать облачный диск и пересылать файлы себе на почту.
- **Перекинуть файл с телефона на компьютер — одно действие.** Перетащите файл в окно, вставьте из буфера или нажмите «+».
- **Отправить сейчас, разобрать потом.** При отправке ничего не нужно выбирать. Папку и теги можно назначить позже.

## Возможности

<table>
  <tr>
    <td width="50%" valign="top"><b>Одна лента на всё</b><br>Заметки, ссылки, фото, видео, документы, музыка и голосовые — сообщения одной ленты, как в мессенджере.</td>
    <td width="50%" valign="top"><b>Синхронизация на всех устройствах</b><br>Отправленное с одного устройства появляется на остальных. Статус синхронизации всегда на виду.</td>
  </tr>
  <tr>
    <td valign="top"><b>Превью файлов</b><br>У PDF, Word, Excel и презентаций в ленте видна первая страница. Фото и видео собираются в альбомы.</td>
    <td valign="top"><b>Встроенный просмотр</b><br>Фото, видео, PDF и плеер для музыки открываются прямо в приложении.</td>
  </tr>
  <tr>
    <td valign="top"><b>Голосовые как в Telegram</b><br>Удерживайте микрофон или смахните вверх, чтобы записывать без рук. Перед отправкой запись можно прослушать.</td>
    <td valign="top"><b>Папки, теги и закреплённые</b><br>Разложить сообщения можно потом. На отправку это не влияет.</td>
  </tr>
  <tr>
    <td valign="top"><b>Поиск</b><br>По тексту, типу, папке, тегам и дате. Ищет и внутри документов, и в расшифровках голосовых.</td>
    <td valign="top"><b>Новое устройство без SSH</b><br>Подключается по QR-коду, ссылке или коду из шести цифр с устройства, которое уже подключено.</td>
  </tr>
  <tr>
    <td valign="top"><b>Сервер ставится из приложения</b><br>Укажите адрес сервера, пароль или SSH-ключ. Приложение покажет каждый этап установки, а если что-то пойдёт не так — журнал.</td>
    <td valign="top"><b>Свой вид на каждой платформе</b><br>Android, macOS, Windows и Linux уже сейчас, iOS скоро. Светлая и тёмная тема.</td>
  </tr>
</table>

## Как это работает

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/how-ru-dark.png">
    <img src=".github/readme/how-ru-light.png" width="880" alt="Телефоны и компьютеры синхронизируются через ваш сервер">
  </picture>
</p>

1. **Установите приложение** на компьютер или телефон.
2. **Подключите сервер.** Укажите адрес, порт и имя пользователя, затем пароль или SSH-ключ. Приложение всё настроит само и сразу откроет ленту.
3. **Добавьте остальные устройства.** Откройте приглашение на уже подключённом устройстве. Новое подключается по QR-коду, ссылке или коду из шести цифр, SSH ему не нужен.

Нужен сервер на Linux с доступом по SSH.
<!-- TODO: уточнить поддерживаемые дистрибутивы и минимум памяти и диска -->

## Скачать

| Платформа | Файл | Установка |
|---|---|---|
| Android (большинство телефонов) | [`StashTrash-android-arm64-v8a.apk`](https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-android-arm64-v8a.apk) | Когда Android спросит, разрешите установку из этого источника. |
| Android (старые 32-битные телефоны) | [`StashTrash-android-armeabi-v7a.apk`](https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-android-armeabi-v7a.apk) | Те же шаги. Выбирайте этот файл, если arm64-v8a не устанавливается. |
| macOS | [`StashTrash-macos.dmg`](https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-macos.dmg) | Откройте образ и перетащите StashTrash в «Программы». Подходит для Mac на Apple Silicon и Intel. |
| Windows (64-бит) | [`StashTrash-windows-x64.zip`](https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-windows-x64.zip) | Распакуйте архив и запустите `stash_trash.exe`. При первом запуске Windows может показать предупреждение, см. ниже. |
| Linux (64-бит) | [`StashTrash-linux-x64.tar.gz`](https://github.com/Salesao/stashtrash/releases/latest/download/StashTrash-linux-x64.tar.gz) | Распакуйте архив в папку и запустите `stash_trash`. Команды ниже. |
| iOS | Скоро | — |

Все версии и список изменений — в [Releases](https://github.com/Salesao/stashtrash/releases).

<details>
<summary><b>macOS не даёт открыть приложение</b></summary>
<br>
Откройте «Системные настройки» → «Конфиденциальность и безопасность». Внизу, рядом с сообщением о StashTrash, нажмите «Всё равно открыть». Это нужно сделать один раз.
</details>

<details>
<summary><b>Windows пишет «Система Windows защитила ваш компьютер»</b></summary>
<br>
Приложение пока не подписано платным сертификатом, поэтому Windows относится к нему с осторожностью. Нажмите «Подробнее», затем «Выполнить в любом случае». Это нужно сделать один раз.
</details>

<details>
<summary><b>Windows пишет, что нет VCRUNTIME140.dll или MSVCP140.dll</b></summary>
<br>
Установите <a href="https://aka.ms/vs/17/release/vc_redist.x64.exe">Microsoft Visual C++ Redistributable (x64)</a> и запустите приложение снова.
</details>

<details>
<summary><b>Как установить и запустить в Linux</b></summary>
<br>

```sh
mkdir StashTrash
tar -xzf StashTrash-linux-x64.tar.gz -C StashTrash
./StashTrash/stash_trash
```

Сборка сделана на Ubuntu 22.04 и требует glibc 2.34 или новее (Ubuntu 22.04, Debian 12, Fedora 35 и новее). Ещё нужны GTK 3, GStreamer и libsecret. В Debian и Ubuntu:

```sh
sudo apt install libgtk-3-0 libgstreamer1.0-0 libgstreamer-plugins-base1.0-0 libsecret-1-0
```

Сборки Linux под ARM пока нет.
</details>

## Скриншоты

Документы, голосовые и музыка:

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/phones-1-dark.png">
    <img src=".github/readme/phones-1-light.png" width="880" alt="Документы с превью, голосовые с мини-плеером и музыка в ленте">
  </picture>
</p>

Поиск, плеер и подключение нового устройства:

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/phones-2-dark.png">
    <img src=".github/readme/phones-2-light.png" width="880" alt="Поиск с фильтрами, полноэкранный плеер и сканер QR-кода">
  </picture>
</p>

На компьютере:

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/desktop-dark.png">
    <img src=".github/readme/desktop-light.png" width="880" alt="StashTrash на компьютере: боковое меню с папками и лента с документами">
  </picture>
</p>

## Вопросы

<details>
<summary><b>Где хранятся мои файлы?</b></summary>
<br>
На вашем сервере: там лежат и файлы, и база.
</details>

<details>
<summary><b>Нужен ли отдельный сервер для каждого устройства?</b></summary>
<br>
Нет. Сервер один, к нему подключаются все ваши устройства.
</details>

<details>
<summary><b>Можно ли обойтись без компьютера?</b></summary>
<br>
Да. Сервер настраивается и с телефона: адрес сервера и пароль или ключ вводятся прямо в приложении.
</details>

<details>
<summary><b>А как же iOS?</b></summary>
<br>
Пока нет: сборка ещё впереди. Когда она будет готова, появится в таблице выше и на странице Releases.
</details>

<details>
<summary><b>Что за вкладка «AI»?</b></summary>
<br>
Этот раздел ещё в разработке. Вкладка уже стоит на своём месте и заработает в одной из следующих версий.
</details>

<details>
<summary><b>Нашёл ошибку или есть идея</b></summary>
<br>
Напишите в <a href="https://github.com/Salesao/stashtrash/issues">Issues</a>. Укажите платформу, версию приложения и что произошло. Если ошибка при установке сервера, приложите журнал из «Настройки» → «Диагностика».
</details>

## Лицензия

Код приложения закрыт. В этом репозитории публикуются сборки и список изменений.

© 2026 Salesao. Все права защищены.

<br>

<p align="center">
  <img src=".github/readme/app-icon.png" width="56" alt="">
  <br>
  <sub>StashTrash — личное хранилище на собственном сервере</sub>
</p>
