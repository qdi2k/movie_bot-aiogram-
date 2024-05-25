# Movie Bot

Телеграм бот для поиска ссылок на бесплатный просмотр интересующих фильмов и сериалов. 
Бот работает на библиотеке Aiogram, использует сервисы google для ассоциативного поиска, 
а также библиотеку Кинопоиска и сервис C_X. В боте реализованна защита от флудинга,
с помощью middlewares. Для парсинга используется BeautifulSoup.
---

### Быстрый старт

1. Склонируйте проект на свой компьютер
2. Создайте файл `.env` и наполните его в предложенном формате
```
TOKEN=123456789 # Токен вашего telegram бота 
```
3. Если у вас нет виртуального окружения, то создайте и  активируйте его
```shell
python -m venv venv
```
```shell
venv\Scripts\activate.bat
```
4. Обновите pip и установите необходимые зависимости
```shell
pip install --upgrade pip
```
```shell
pip install -r requirements.txt
```
5. Запустите run.py
```shell
python run.py
```
---
Ссылка на бота: https://t.me/Guarava_bot <br>
Для связи: https://t.me/qdi2k <br>

