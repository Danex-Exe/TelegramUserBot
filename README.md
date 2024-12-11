# Telegram-бот на базе Pyrogram

## Описание

Данный проект представляет собой Telegram-бота, написанного на Python с использованием библиотеки **Pyrogram**. Бот предлагает разнообразные функции, включая автоматические ответы, управление голосовыми сообщениями и распознавание речи. Он может выполнять код на Python и генерировать ответы с использованием ИИ, что значительно расширяет возможности общения в Telegram.

## Основные функции

1. **Автоответы:** Бот может автоматически отвечать на сообщения, соответствующие заданным ключевым словам.

2. **Создание пользовательских команд:** Пользователи могут создавать свои команды и настраивать описание команд и псевдонимы.

3. **Анимации:** Бот поддерживает анимации, которые можно запускать и управлять их скоростью.

4. **Работа с голосовыми сообщениями:** Бот может загружать и конвертировать голосовые сообщения в текст, используя технологию распознавания речи.

5. **GPT-ответы:** Бот интегрирован с GPT для генерации ответов на основе пользовательского ввода.

6. **Безопасность и конфиденциальность:** Все данные хранятся в локальных JSON-файлах, обеспечивая безопасность и возможность редактирования.

## Установка и настройка

### Предварительные требования

Убедитесь, что у вас установлены следующие библиотеки:

- **Pyrogram**
- **FuzzyWuzzy**
- **Pydub**
- **SpeechRecognition**
- **requests**
- **aiohttp**

Вы можете установить их с помощью pip:

```bash
pip install -r requirements.txt
```

### Настройка бота

1. **Создайте файл конфигурации:**
   Скопируйте файл `data.json` из `configs` и откройте его для редактирования. Заполните необходимые параметры: `api_id`, `api_hash` и имя бота.

2. **Запустите бота:**
   Используя команду `python main.py`, запустите бота. Он готов к работе в Telegram.

## Использование

После запуска бот будет слушать сообщения и отвечать в соответствии с заданными настройками. Поддерживается множество команд, таких как `/help`, `/animation`, `/key`, которые помогут пользователям настроить бота в соответствии с их требованиями.

## Заключение

Этот бот — мощный инструмент для взаимодействия с пользователями в Telegram, который сочетает в себе возможности автоматизации, использования ИИ и творчества. Если у вас есть идеи для улучшения или дополнительные функции, пожалуйста, создайте pull request!

## Контрибьюция

Мы приветствуем общественный вклад! Если у вас есть идеи, пожалуйста, создайте форк репозитория и отправьте pull request. Ваш вклад поможет улучшить проект!
