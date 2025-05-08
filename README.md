# tera-guide (classic)

## Patch v31.04 and v33.08 (Akeron/Nova)

### :star: Available in TERA Toolbox for patch 31.04
* Fully compatible with [TERA Toolbox for patch 31.08](https://github.com/tera-classic-toolbox/tera-toolbox).   
  Automatic install from **Get More Mods** tab.

* Полностью совместимо с [TERA Toolbox для патча 31.08](https://github.com/tera-classic-toolbox/tera-toolbox).   
  Автоматическая установка через вкладку **Скачать модули**.

### :star: Available in TERA Toolbox for patch 33.08 (Akeron/Nova)
* Information is available on Discord: https://discord.gg/uCgpcmvpfp
* Информация доступна в Discord: https://discord.gg/uCgpcmvpfp

### :information_source: Manual installation
The tera-guide and [tera-guide-core](https://github.com/tera-classic-mods/tera-guide-core) are already compatible with this patch.   
For the guides to work you need a get compatible versions of **library** (classic) and **tera-guide-core** (classic):
1. Download **library** from **[here](https://github.com/tera-classic-toolbox/library/archive/refs/heads/master.zip)** and place it to you **mods** folder named as **"library"**.
2. Download **tera-guide-core** from **[here](https://github.com/tera-classic-mods/tera-guide-core/archive/refs/heads/master.zip)** and place it to you **mods** folder named as **"tera-guide-core"**,   
   not "tera-guide-core-master".

### :information_source: Ручная установка
Модули tera-guide и [tera-guide-core](https://github.com/tera-classic-mods/tera-guide-core) совместимы с данным патчем уже сейчас.   
Для работы гайдов вам потребуется установка совместимой версии **library** (classic) и **tera-guide-core** (classic):
1. Скачайте **library** **[здесь](https://github.com/tera-classic-toolbox/library/archive/refs/heads/master.zip)** и поместите в вашу папку **mods** как **"library"**.
2. Скачайте **tera-guide-core** **[здесь](https://github.com/tera-classic-mods/tera-guide-core/archive/refs/heads/master.zip)** и поместите в вашу папку **mods** как **"tera-guide-core"**,   
   а не "tera-guide-core-master".

---

## Description / Описание

The dungeon guide module with Text-to-speech notifications, display hints on screen and drawing zones of bosses attacks and mechanics. Available English and Russian languages (detects automatically).

Модуль подсказок по данжам с возможностью голосовых уведомлений, вывод подсказок в чат или на экран, а также отрисовка зон атак боссов и механик. Поддерживаются Русский и Английский языки (определяются автоматически).

## Dependencies / Зависимости
* **library** - https://github.com/tera-classic-toolbox/library
* **tera-guide-core** - https://github.com/tera-classic-mods/tera-guide-core

When using TeraToolbox, all dependencies will be installed automatically.   
При использовании TeraToolbox, все зависимости будут установлены автоматически.

## Commands / Команды
Toolbox(/8) | Command description | Описание команды
--- | --- | ---
**guide** | Module on/off | Вкл./выкл. модуля
**guide&nbsp;gui** | Show module GUI| Показать графический интерфейс
**guide&nbsp;voice**<br>(default: off) | Text-to-speech (TTS) notices on/off, speech rate is set by command **guide `1`~`10`** | Вкл./выкл. голосовых уведомлений (TTS), скорость чтения задается командой **guide `1`~`10`**
**guide&nbsp;lNotice**<br>(default: off) | Send notices to chat channel "Notice" instead of on-screen messages on/off | Вкл./выкл. отправки уведомлений в канал чата "Важно" вместо показа экранных сообщений
**guide&nbsp;gNotice**<br>(default: off) | Send notices to party chat channel on/off | Вкл./выкл. отправки уведомлений в канал чата группы
**guide&nbsp;`auto`/`en`/`ru`**<br>(default: auto) | Set guide language | Выбор языка перевода
**guide&nbsp;`1`~`10`**<br>(default: 2) | Set TTS speech rate | Регулировка скорости чтения голосовых сообщений
**guide&nbsp;spawnObject**<br>(default: on) | Spawn marker objects on/off | Вкл./выкл. спавна маркировочных объектов
**guide&nbsp;stream**<br>(default: off) | Streamer Mode on/off (hide all notices and objects, TTS will played) | Вкл./выкл. режима стримера (скрывает все уведомления и маркеры, TTS будет проигрываться)
**guide&nbsp;dungeons** | List of all supported dungeons and its ids | Список всех поддерживаемых данжей и их id
**guide&nbsp;verbose&nbsp;`id`**<br>(default: on for all) | Send notices for specified by `id` dungeon on/off | Вкл./выкл. всех уведомлений для данжа, где `id` - идентификатор данжа
**guide&nbsp;spawnObject&nbsp;`id`**<br>(default: on for all) | Spawn marker objects for specified by `id` dungeon on/off | Вкл./выкл. спавна объектов для данжа, где `id` - идентификатор данжа
**guide&nbsp;help** | List of supported commands | Вывод поддерживаемых команд

## Supported dungeons / Поддерживаемые данжи

id | Dungeon name | Название данжа
--- | --- | ---
9054 | Bathysmal Rise (Hard) | Глубинный Храм (сложно)
9056 | Timescape (Hard) | Хроноплоскость (сложно)
9057 | Akeron's Inferno (Hard) | Акероново пекло (сложно)
9067 | Demokron Factory (Hard) | Лаборатория Берна (сложно)
9068 | Shadow Sanguinary (Hard) | Убежище Дуриона (сложно)
9754 | Bathysmal Rise | Глубинный Храм
9759 | Forsaken Island (Hard) | Остров Мертвых (сложно)
9768 | Shadow Sanguinary | Убежище Дуриона

## Notices settings / Настройка уведомлений

* On screen (on bottom side) and chat notices, if **lNotice** parameter is *on*.   
  Уведомления на экране (в нижней части), а также в чате, если параметр **lNotice** - *включен*.   
  ![](https://i.imgur.com/BPlK58M.png)

* When **gNotice** parameter is *on*, notices will also be sent to party chat channel.   
  Если параметр **gNotice** был *включен*, уведомления также будут отправляться в канал чата группы.   

* The message on top side of the screen, if **lNotice** parameter is *off* (by default).   
  Сообщение в верхней части экрана, если параметр **lNotice** - *выключен* (по-умолчанию).   
  ![](https://i.imgur.com/r2bb8Wc.png)   
  You can set the color for this type of notices using the commands or GUI (also change color in the Toolbox chat).   
  Возможен выбор цвета для этого вида уведомлений при помощи команд или графического интерфейса (также изменяется цвет в чате Toolbox).

* When Streamer Mode is *on* (**stream** parameter), all text notices ONLY sent to Toolbox(/8) chat channel, but TTS notices will be played.   
  Если *включен* режим стримера (парам. **stream**), все текстовые уведомления будут отправляться ТОЛЬКО в канал чата Toolbox(/8), однако голосовые уведомления будут проигрываться.

* To disable or enable TTS notifications, use the **guide voice** command.   
  Для отключения или включения голосовых уведомлений используется команда **guide voice**.

## Module GUI / Графический интерфейс

* When you enter the **guide gui** command, the module GUI is displayed, allowing you to change basic settings.   
  При вводе команды **guide gui** отображается графический интерфейс модуля, позволяющий осуществить основные настройки.   
  ![](https://i.imgur.com/72hDCvQ.png)

## More information / Дополнительная информация

* Developers wiki: https://github.com/tera-classic-mods/tera-guide-core/wiki
* For questions and suggestions, contact via Discord: **JKQ**

## Credits
- **[Kasea](https://github.com/Kaseaa)** - Original developer of Tera-Guide module
- **[michengs](https://github.com/michengs)** - Author of base code for most guides and module core
- **[ZC](https://github.com/tera-mod)** - Provided coordinates for rendering attack areas and mechanics
- **[Kuroine](https://github.com/Kuroine)** - Author of base code for the DA guide
- **[Multarix](https://github.com/Multarix)** - Author of the RR guide and also making changes to the English translation
- **[Owyn](https://github.com/Owyn)** - Developer of great guides for RK-9, AA and GV, whose code was used
- **[Emilia](https://github.com/emilia-s2)** - Author of Portuguese translation and guardian guides
- **[Loliconera](https://github.com/Loliconera)** - Author of Spanish translation
- **[ITunk](https://github.com/GrafNikola)** - Author of initial Russian translation
