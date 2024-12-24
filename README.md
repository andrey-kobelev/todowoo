# Todo List

> Веб сайт на котором вы можете создавать список дел.

**Что может пользователь:**
- Завести свой аккаунт
- Создавать список дел в личном кабинете
- Проводить над записью различные операции:
	- Помечать как выполненные, 
	- Удалять,
	- Редактировать существующие записи,
	- Помечать как важные и они подсветятся красным цветом и всплывут на первый план списка. 
	- Помечать как выполненные, после чего запись попадет в список выполненных с пометкой когда и во сколько она была выполнена.


## Как развернуть проект локально

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/andrey-kobelev/todo_app.git
```

```  
cd todo_app
``` 

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env  
```

```
source env/bin/activate  
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip  
```

```
pip install -r requirements
```

Выполнить миграции:

```
python3 manage.py migrate  
```

Запустить проект:

```
python3 manage.py runserver  
```


## Автор

[Kobelev Andrey](https://github.com/andrey-kobelev)

## Стек

- [Python 3.9](https://www.python.org/downloads/release/python-390/)
- [Django5.1.4](https://docs.djangoproject.com/en/5.1/releases/5.1.4/)