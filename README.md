<img align="right" src="https://i.imgur.com/zrE80HY.png" height="200" width="200">

# JMusicBot на русском

[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://github.com/Amitexing/JMusicBot-Rus/releases/latest)
[![Stars](https://img.shields.io/github/stars/jagrosh/MusicBot.svg)](https://github.com/Amitexing/JMusicBot-Rus/stargazers)
[![Release](https://img.shields.io/github/release/jagrosh/MusicBot.svg)](https://github.com/Amitexing/JMusicBot-Rus/releases/latest)
[![License](https://img.shields.io/github/license/jagrosh/MusicBot.svg)](https://github.com/Amitexing/JMusicBot-Rus/blob/master/LICENSE)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://discord.gg/0p9LSGoRLu6Pet0k)<br>
[![CircleCI](https://img.shields.io/circleci/project/github/jagrosh/MusicBot/master.svg)](https://circleci.com/gh/jagrosh/MusicBot)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/gdu6nyte5psj6xfk/branch/master?svg=true)](https://ci.appveyor.com/project/jagrosh/musicbot/branch/master)
[![CodeFactor](https://www.codefactor.io/repository/github/jagrosh/musicbot/badge)](https://www.codefactor.io/repository/github/jagrosh/musicbot)

Кроссплатформенный музыкальный бот Discord с понятным интерфейсом, который легко настроить и запустить самостоятельно!

[![Установка](http://i.imgur.com/VvXYp5j.png)](https://jmusicbot.com/setup)

## Особенности
 * Простота запуска (просто убедитесь, что установлена Java, и запустите!)
 * Быстрая загрузка песен
 * Не требуется никаких внешних ключей (кроме токена бота Discord)
 * Плавное воспроизведение
 * Настройка для конкретного сервера для роли "ди-джея", который может модерировать музыку
 * Чистые и красивые меню
 * Поддерживает множество сайтов, включая Youtube, Soundcloud и другие
 * Поддерживает множество онлайн-радио / потоков
 * Поддержка локальных файлов
 * Поддержка плейлистов (как веб / youtube, так и локальных)

## Поддерживаемые источники и форматы
JMusicBot поддерживает все источники и форматы, поддерживаемые [lavaplayer](https://github.com/sedmelluq/lavaplayer#supported-formats ):
### Источники
 * YouTube
 * SoundCloud
 * Bandcamp
 * Vimeo
 * Подергивание потоков
 * Локальные файлы
 * URL-адреса HTTP
### Форматы
 * MP3
 * FLAC
 * WAV
 * Matroska/WebM (кодеки AAC, Opus или Vorbis)
 * MP4/M4A (кодек AAC)
 * Потоки OGG (кодеки Opus, Vorbis и FLAC)
 * Потоки AAC
 * Потоковые плейлисты (M3U и PLS)

## Пример
![Пример загрузки...](https://i.imgur.com/kVtTKvS.gif)

## Протестировать бота
Вы можете протестировать бота на [Discord сервере Anicloud](https://discord.gg/A7zrZ5Y )

## Установка
1. Установите Java (Бот написан под Java 16)
2. Скачайте или скомпилируйте последний JMusicBot-Rus-X.Y.Z.jar (После компиляции .jar файл будет называться JMusicBot-Rus-X.Y.Z-All.jar)
3. Запуск бота
 3.1 На Windows просто откройте файл двойным кликом
 3.2 Используйте команду для запуска java -Dnogui=true -jar JMusicBot-Rus-X.Y.Z.jar
 3.3 Используйте команду для запуска nohup java -Dnogui=true -jar JMusicBot-X.Y.Z.jar & для запуска в фоновом режиме (Только для Linux)
4. Следуюйте инструкциям в консоли или заполните config.txt

Пожалуйста, ознакомьтесь с [Страница настройки](https://jmusicbot.com/setup ), чтобы запустить этого бота самостоятельно!


## Вопросы/Предложения/Сообщения об ошибках
**Пожалуйста, ознакомьтесь с [Списком проблем](https://github.com/jagrosh/MusicBot/issues ), прежде чем предлагать функцию **. Если у вас есть вопрос, вам нужна помощь в устранении неполадок или вы хотите провести мозговой штурм новой функции, пожалуйста, начните [Обсуждение](https://github.com/jagrosh/MusicBot/discussions ). Если вы хотите предложить функцию или сообщить о воспроизводимой ошибке, пожалуйста, откройте [Проблема](https://github.com/jagrosh/MusicBot/issues ) в этом репозитории. Если вам нравится этот бот, обязательно добавьте звездочку к библиотекам, которые делают это возможным: [**JDA**](https://github.com/DV8FromTheWorld/JDA ) и [**lavaplayer**](https://github.com/sedmelluq/lavaplayer )!

## Редактирование
Этот бот (и исходный код здесь) может быть нелегко редактировать неопытным программистам. Основная цель публикации исходного кода - показать возможности библиотек, позволить другим понять, как работает бот, и позволить тем, кто разбирается в разработке java, JDA и Discord bot, внести свой вклад. Существует множество требований и зависимостей, необходимых для его редактирования и компиляции, и людям, желающим внести изменения самостоятельно, поддержка предоставляться не будет. Вместо этого рассмотрите возможность создания запроса функции (см. раздел выше). Если вы решите внести изменения, пожалуйста, сделайте это в соответствии с лицензией Apache 2.0.
