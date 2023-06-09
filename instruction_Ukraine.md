## Передумови

- Переконайтеся, що на вашій системі встановлено **Python** версії 3.10+.
- Переконайтеся, що ви вмієте працювати з консоллю та запускати команди в ній

## Встановлення

1. Клонуйте репозиторій, виконавши в консолі наступну команду

```
git clone https://github.com/seesmof/twitch-ai-chatbot.git
```

Або перейдіть за цим [посиланням](https://github.com/seesmof/twitch-ai-chatbot/archive/refs/tags/1.0.0.zip) і розархівуйте архів до вашої системи.

2. Встановіть необхідні залежності, виконавши в консолі наступну команду

```
pip install -r requirements.txt
```

3. Перейдіть за [посиланням](https://twitchtokengenerator.com/), виберіть опцію `Bot Chat Token`, коли з'явиться відповідний діалог, і скопіюйте параметр `Access Token`.

4. Виконайте [ці інструкції](./more_on_vars_Ukrainian.md), щоб налаштувати необхідні змінні.

5. Запустіть бота за допомогою наступної команди:

```
python main.py
```

Або просто запустивши виконуваний файл `main.py` на вашому комп'ютері. І все готово! Бот буде працювати до тих пір, поки запущений файл.

## Використання

Після запуску бот буде слухати повідомлення у вказаному каналі (або каналах) і генерувати відповідь на основі запиту.

Щоб згенерувати повідомлення, згадайте бота у своєму повідомленні, використовуючи `@<ім'я вашого бота>`. Після цього бот згенерує відповідь на основі введеного тексту і відправить її в чат.

Бот має затримку між повідомленнями 20 секунд. Якщо ви хочете змінити цей параметр, перейдіть до файлу `main.py` і змініть число в дужках у рядку 25.
