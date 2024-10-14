### Приложение для Благотворительного фонда поддержки котиков QRKot. Фонд собирает пожертвования на различные целевые проекты: на медицинское обслуживание нуждающихся хвостатых, на обустройство кошачьей колонии в подвале, на корм оставшимся без попечения кошкам — на любые цели, связанные с поддержкой кошачьей популяции.

## Используемые технологии
* Python 3.9
* FastAPI
* SQLAlchemy
* Pydantic
* Alembic
* Uvicorn

## Запуск проекта
Клонировать проект с GitHub

```git clone git@github.com:<Твой_Git_Login>/backend_test_homework.git ```

Создание виртуального окружения

```python -m venv venv ```

Активация виртуального окружения

```source venv/Scripts/activate ```

После активации обновляем pip

``` python -m pip install --upgrade pip ```
Установка пакетов по файлу

```pip install -r requirements.txt ```

## Использование и запуск проекта
Создание в корне проект файла .env со следующим содержанием
* ```APP_TITLE=Благотворительного фонда поддержки котиков QRKot```
* ```DATABASE_URL=sqlite+aiosqlite:///./fastapi.db```
* ```SECRET='Ваш секретный код'```
* ```FIRST_SUPERUSER_EMAIL='Ваш e-mail суперпользователя'```
* ```FIRST_SUPERUSER_PASSWORD='Ваш пароль суперпользователя' ```

Создание файла миграции

``` alembic revision```

Применение миграций

```alembic upgrade ```

Запуск проекта

```uvicorn app.main:app --reload ```

## Создание отчета.
Добавление в файл .env новых данных
* ```TYPE=```
* ```PROJECT_ID=```
* ```PRIVATE_KEY_ID=```
* ```PRIVATE_KEY=```
* ```CLIENT_EMAIL=```
* ```CLIENT_ID=```
* ```AUTH_URI=```
* ```TOKEN_URI=```
* ```AUTH_PROVIDER_X509_CERT_URL=```
* ```CLIENT_X509_CERT_URL=```
* ```EMAIL=``` 

Автор
Екатерина https://github.com/Kate1109
