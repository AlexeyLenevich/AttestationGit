# подсказки
## Основные команды

### Команда смены директории
```sh
cd C:\folder_name
```

### Команда отображения текущей директории MacOs, Linux
```sh
pwd
```

### Листинг текущей директории 
Windows:
```sh
dir
```
MacOs, Linux:
```sh
ls
```

### Удаление файла в Win:
```sh
del "имя файла"
```
MacOs, Linux
```sh
rm "имя файла"
```
Установка Git в созданную папку
```sh
git init 
```

Добавление файла в git
```sh
git add 
```

### Показ версий
```sh
git log
```

### Запись версии
```sh
git commit -m "Комментарий"
```

### Выйти из режима отображения commit-ов
```sh
нажать q
```

### отображение инфы в компактном виде
```sh
git log --oneline
```

### Переход между состояниями (версиями)
```sh
git checkout "*"id версии"
```
### Отражение изменений, внесённых в файл до сохранения (до commit)
```sh
git diff "id версии"
```

### Вернуться в актуальное состояние (вверх ветки)
```sh
git checkout master
```
#### **Заметка:** *переключение между ветками происходит посредством команды git checkout "имя файла". Например: git checkout pie1*

## Ветки
### Показ веток
```sh
git branch
```
### Создание ветки pie1
```sh
git branch pie1
```

## Работа с текстом

### **Ввод полужирного текста**
```sh
**Text**
```

### *Ввод курсива*
```
*Курсив*
```
#### Заметка: 
*Полужирный текст либо курсив можно также вводить с помощью нижнего подчёркивания.* Например: _вот так_ и __вот так__.
Это служит для комбинирования курсива и полужирного: _**вот так**_.

>Цитирование в языке
>> MarkDown
```sh
> 1-ый уровень
>> 2-ой уровень
```

* С
1. П
* И
2. С
* К
3. И
#### Ненумерованный список
```sh
* элемент 1
* элемент 2
```
#### Нумированный список
```sh
1. элемент 1
1. элемент 2
```


### Интернет-ссылки

Текст [пример ссылки](www.google.com "подсказка")



## Особенности сохранения текста

"*Какой-то текст" - его мы сохраняем через add до состояния Modified (зелёный)
При добавлении "новый текст" без сохранения "какой-то текст" в commit, стоит выбор: добавлять ли в commit только "какой-то текст", либо ещё и "новый текст*"

### Новая строка в языке MarkDown:
```sh
Привет. Как дела?

Круто!
```

*Чтобы вставить картинку в текст, необходима команда:* 

**! [ ] ( )**

Например:
![Красивый вид](vid.jpg)

## Работа с удалёнными репозиториями

### Выбор репозитория для выгрузки
```sh
git remote add origin https://github.com/AlexeyLenevich/AttestationGit.git
```
### Определение основной ветки репозитория
```sh
git branch -M main
```

### Загрузка / обнолвение инфы на GitHub
```sh
git push -u origin main
```

### Выгрузка инфы из GitHub на комп
```sh
git pull
```

### Создание копии репозитория в GitHub для дальнейшего редактирования
```sh
Кнопка fork в GitHub
```

### Добавление форкнутого репозитория локальную папку (на комп)
```sh
git clone https://github.com/CanUFeelMyHeart/brave3690.git
```