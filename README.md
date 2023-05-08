### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:syberflea/kittygram2plus.git
```

```
cd kittygram2plus
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source env/bin/activate
```

Или
```
.\env\scripts\activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
