Запустить проект можно следующим образом:

1) Клонируйте репозиторий и перейдите в него в командной строке:

```
git clone https://github.com/sapphirehead/api_final_yatube.git
```

```
cd api_final_yatube
```

2) Cоздайте и активируйте виртуальное окружение:

```
python3 -m venv venv
```

либо для Windows:

```
python -m venv venv
```

затем:

```
source venv/bin/activate
```

либо для Windows:

```
venv\Scripts\activate либо venv\Scripts\activate.bat
```

3) Обновите pip:

```
python3 -m pip install --upgrade pip
```

4) Установите зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

5) Выполните миграции:

```
python3 manage.py migrate
```

Запустите проект:

```
python3 manage.py runserver
```