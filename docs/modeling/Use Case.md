# Use Case
# Сценарии пользователя
## 1. Просмотр содержимого раздела жесткого диска
### Базовый сценарий
1) Пользователь активирует элемент ComboBox c выпадающим списком разделов жесткого диска.
2) Выбор нужного раздела жесткого диска нажатием левой кнопки мыши.
3) Система обрабатывает нажатие и обновляет содержимое выбраного раздела.
4) Пользователь видит обновленный список содержимого.
### Альтернативный сценарий
1) Пользователю отображается один из разделов по умолчанию.
2) Пользователь просматривает содержимое раздела.
## 2. Просмотр содержимого каталога
### Предусловия
Пользователем выбран нужный раздел диска(сценарий 1. Просмотр содержимого раздела жесткого диска) 
### Базовый сценарий
1) Пользователь наводит курсор мыши на нужный каталог и два раза нажимает левую кнопку мыши.
2) Система обрабатывает двойное нажатие кнопки.
3) Система определяет тип выделенного элемента.
4) Система определяет содержимое каталога.
5) Пользователь видит содержимое выбраного каталога.
### Альтернативный сценарий
1) Пользователь наводит курсор мыши на нужный каталог и два раза нажимает левую кнопку мыши.
2) Система обрабатывает двойное нажатие кнопки.
3) Система сообщает пользователю о невозможности открытия каталога.
4) Пользователь выбирает другой каталог. 
## 3. Открытие файла
### Предусловия
Пользователем выбран нужный раздел диска(сценарий 1. Просмотр содержимого раздела жесткого диска) 
### Базовый сценарий
1) Пользователь наводит курсор мыши на выбранный файл и два раза нажимает левую кнопку мыши.
2) Система обрабатывает двойное нажатие кнопки.
3) Система определяет тип выбраного элемента.
4) Система ищет программу в операционной системе, которая откроет файл.
5) Выбранный файл открывается в найденной программе.
### Альтернативный сценарий
1) Пользователь наводит курсор мыши на выбранный файл и два раза нажимает левую кнопку мыши.
2) Система обрабатывает двойное нажатие кнопки.
3) Система определяет тип выбраного элемента.
4) Система не находит программу, которая открывает файл.
5) Система информирует пользователя о невозможности открытия файла.
### 4. Просмотр сведений об элементе файловой системы
### Предусловия
Пользователем выбран нужный ему раздел диска и каталог.
### Базовый сценарий
1) Пользователь наводит курсор на нужный элемент.
2) Пользователь нажимает правую кнопку мыши.
3) Система обрабатывает нажатие.
4) Система отображает пользователю информацию о файле.
### 5. Поиск по имени файла
### Базовый сценарий
1) Пользователь выбирает директорию для поиска.
2) Пользователь вводит имя файла в панели для поиска.
3) Система осуществляет рекурсивный поиск во всех вложенных каталогах.
### Успешный результат
Пользователю отображается найденый файл.
### Альтернативный результат
Пользователь видит сообщение об отсутствии запрашиваемого файла.
### 6. Копирование файла
### Предусловия
Пользователем выбран нужный ему раздел диска и каталог.
### Базовый сценарий
1) Пользователь выбирает нужный файл.
2) Пользователь выбирает путь назначения(выбор каталога сценарий 2).
3) Пользователь нажимает кнопку копирование.
4) Система обрабатывает нажатие кнопки и начинает выполнение операции.
5) Система информирует пользователя о статусе выполнения операции.
### Альтернативный сценарий
1) Пользователь нажимает кнопку копирование.
2) Система обрабатывает нажатие кнопки.
3) Система оповещает пользователя об отсутствии копируемого файла.
### 7. Перемещение файла
### Предусловия
Пользователем выбран нужный раздел диска и каталог.
### Базовый сценарий
1) Пользователь выбирает нужный файл.
2) Пользователь выбирает путь назначения(выбор каталога сценарий 2).
3) Пользователь нажимает кнопку перемещение.
4) Система обрабатывает нажатие кнопки и начинает выполнение операции.
5) Система информирует пользователя о статусе выполнения операции.
### Альтернативный сценарий
1) Пользователь нажимает кнопку перемещение.
2) Система обрабатывает нажатие кнопки.
3) Система оповещает пользователя об отсутствии перемещаемого файла.
### 8. Удаление файла
### Предусловия
Пользователем выбран нужный раздел диска и каталог.
### Базовый сценарий
1) Пользователь выбирает нужный файл.
2) Пользователь нажимает кнопку удалить.
4) Система обрабатывает нажатие кнопки и начинает выполнение операции.
5) Система информирует пользователя о статусе выполнения операции.
### Альтернативный сценарий
1) Пользователь нажимает кнопку удалить.
2) Система обрабатывает нажатие кнопки.
3) Система оповещает пользователя о том, что файл не выбран.
### 9. Переименование файла
### Предусловия
Пользователем выбран нужный раздел диска и каталог.
### Базовый сценарий
1) Пользователь выбирает нужный файл.
2) Пользователь нажимает кнопку переименование.
4) Система обрабатывает нажатие кнопки.
5) Файл успешно переименован.
### Альтернативный сценарий
1) Пользователь выбирает нужный файл.
2) Пользователь нажимает кнопку переименование.
3) Система обрабатывает нажатие кнопки.
4) Система оповещает пользователя о том, что файл с таким именем уже существует.
5) Пользователь вводит другое имя файла.
### 10. Создание файла
### Предусловия
Пользователем выбран нужный раздел диска и каталог.
### Базовый сценарий
1) Пользователь нажимает кнопку создать.
2) Система отображает пользователю окно с полем для ввода имени.
3) Пользователь вводит имя файла.
4) Система успешно создает файл.
### Альтернативный результат
1) Пользователь нажимает кнопку создать.
2) Система отображает пользователю окно с полем для ввода имени.
3) Пользователь вводит имя файла.
4) Система сообщает пользователю о существовании файла с таким именем.
5) Пользователь вводит новое имя файла.