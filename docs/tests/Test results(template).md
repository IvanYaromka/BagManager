# ОС - Windows 10
## UseCases
Идентификатор  | Назначение | Сценарий | Ожидаемый результат | Фактический результат | Оценка
--|--|--|--|--|--
#1U | Проверка отображения содержимого  выбранного диска | Активируется элемент ComboBox c выпадающим списком разделов жесткого диска. Выбирается нужный раздел щелчком левой кнопки мыши | Отображается список папок и файлов диска | Отображается список папок и файлов диска | Пройден 
#2U | Проверка отображения содержимого диска, выбранного по умолчанию | Приложение запущено впервые | Отображается список элементов одного из разделов жесткого диска | Отображается список элементов одного из разделов жесткого диска | Пройден
#3U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение содержимого выбранного каталога | Отображается содержимое выбранного каталога | Пройден
#4U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение сообщения об ошибке открытия папки | Отображается сообщение об ошибке | Пройден
#5U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Открытие файла соответсвующей программой | Открытие .pdf в AdobeReader | Пройден
#6U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Сообщение об ошибке открытии файла | Отображается окно с ошибкой | Пройден
#7U | Проверка отображения информации о папке или файле | Нажатие правой кнопки мыши по одному из элементов в списке | Отображение окна с информацией о выбранном элементе | Отображается информация о файле | Пройден
#8U | Проверка операции копирования | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ходом операции | Успешное завершение операции | Пройден
#9U | Проверка операции копирования | Нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#10U | Проверка операции перемещения | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ходом операции | Отображение хода операции и ее завершение | Пройден
#11U | Проверка операции перемещения | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#12U | Проверка операции удаления | Выбор левой кнопкой мыши в одном из списков файла или папки; нажатие кнопки удаление в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ходом операции | Отображение окна с ходом удаления и успешное удаление | Пройден
#13U | Проверка операции удаления | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Отображение окна с ошибкой | Провален
#14U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Создание нового файла и обновление содержимого каталога | Создан новый файл | Пройден
#15U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Создание нового каталога и обновление содержимого текущего | Создан новый каталог | Пройден
#16U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Появление окна с сообщением о существовании такого файла и запросом ввода нового имени файла | Введено новое имя и создан новый файл | Пройден
#17U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Появление окна с сообщением о существовании такого каталога и запросом ввода нового имени каталога | Введено новое имя и создан новый каталог | Пройден
#18U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне нового имени | Переименование выбранного элемента и обновление содержимого текущего | Введено имя и каталог переименован| Пройден
#19U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне имени, которое совпадает с именем уже существующего элемента | Появление окна с сообщением о существовании такого элемента и запросом ввода нового имени | Повторно введено имя и каталог переименован| Пройден
## Нефункциональные требования
Идентификатор  | Назначение | Сценарий | Ожидаемый результат | Фактический результат | Оценка
--|--|--|--|--|--
#1NF | Проверка доступности приложения | Запуск приложения. Ожидание на протяжении 5мин. | Приложение работает по истечении заданного времени | Работоспособность приложение сохранилась после 13мин в фоновом режиме | Пройден
#2NF | Проверка безопасности использования | Выбрать системный файл. Нажать кнопку удалить | Сообщение об ошибке удаления файла | Удаление не произошло | Пройден
#3NF | Проверка простоты совершения операций | Выбор исходного файла для копирования. Выбор путь назначения. Нажать кнопку копирование. Подсчитать количество совершенных действий. Произвести операцию копирования стандартными средствами ОС. Подсчитать количество действий | Количество действий, затрачиваемых на операцию копирования меньше, чем стандартными средствами ОС. | Средствами ОС - 7 действий, программой - 5. | Пройден
# ОС - Linux
## UseCases
Идентификатор  | Назначение | Сценарий | Ожидаемый результат | Фактический результат | Оценка
--|--|--|--|--|--
#1U | Проверка отображения содержимого  выбранного диска | Активируется элемент ComboBox c выпадающим списком разделов жесткого диска. Выбирается нужный раздел щелчком левой кнопки мыши | Отображается список папок и файлов диска | Отображается список папок и файлов диска | Пройден 
#2U | Проверка отображения содержимого диска, выбранного по умолчанию | Приложение запущено впервые | Отображается список элементов одного из разделов жесткого диска | Отображается список элементов одного из разделов жесткого диска | Пройден
#3U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение содержимого выбранного каталога | Отображается содержимое выбранного каталога | Пройден
#4U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение сообщения об ошибке открытия папки | Отображается сообщение об ошибке | Пройден
#5U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Открытие файла соответсвующей программой | Открытие .pdf в AdobeReader | Пройден
#6U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Сообщение об ошибке открытии файла | Отображается окно с ошибкой | Пройден
#7U | Проверка отображения информации о папке или файле | Нажатие правой кнопки мыши по одному из элементов в списке | Отображение окна с информацией о выбранном элементе | Отображается информация о файле | Пройден
#8U | Проверка операции копирования | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ходом операции | Успешное завершение операции | Пройден
#9U | Проверка операции копирования | Нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#10U | Проверка операции перемещения | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ходом операции | Операция не завершилась | Провален
#11U | Проверка операции перемещения | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#12U | Проверка операции удаления | Выбор левой кнопкой мыши в одном из списков файла или папки; нажатие кнопки удаление в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ходом операции | Отображение окна с ходом удаления и успешное удаление | Пройден
#13U | Проверка операции удаления | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Отображение окна с ошибкой | Провален
#14U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Создание нового файла и обновление содержимого каталога | Создан новый файл | Пройден
#15U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Создание нового каталога и обновление содержимого текущего | Создан новый каталог | Пройден
#16U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Появление окна с сообщением о существовании такого файла и запросом ввода нового имени файла | Введено новое имя и создан новый файл | Пройден
#17U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Появление окна с сообщением о существовании такого каталога и запросом ввода нового имени каталога | Введено новое имя и создан новый каталог | Пройден
#18U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне нового имени | Переименование выбранного элемента и обновление содержимого текущего | Введено имя и каталог исчез из исходной директории| Провален
#19U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне имени, которое совпадает с именем уже существующего элемента | Появление окна с сообщением о существовании такого элемента и запросом ввода нового имени | Повторно введено имя и каталог исчез из исходной директории| Провален
## Нефункциональные требования
Идентификатор  | Назначение | Сценарий | Ожидаемый результат | Фактический результат | Оценка
--|--|--|--|--|--
#1NF | Проверка доступности приложения | Запуск приложения. Ожидание на протяжении 5мин. | Приложение работает по истечении заданного времени | Работоспособность приложение сохранилась после 8 мин в фоновом режиме | Пройден
#2NF | Проверка безопасности использования | Выбрать системный файл. Нажать кнопку удалить | Сообщение об ошибке удаления файла | Удаление не произошло | Пройден
#3NF | Проверка простоты совершения операций | Выбор исходного файла для копирования. Выбор путь назначения. Нажать кнопку копирование. Подсчитать количество совершенных действий. Произвести операцию копирования стандартными средствами ОС. Подсчитать количество действий | Количество действий, затрачиваемых на операцию копирования меньше, чем стандартными средствами ОС. | Средствами ОС - 9 действий, программой - 6. | Пройден
# Работа с USB-флэш-накопителем
## UseCases
Идентификатор  | Назначение | Сценарий | Ожидаемый результат | Фактический результат | Оценка
--|--|--|--|--|--
#1U | Проверка отображения содержимого  выбранного диска | Активируется элемент ComboBox c выпадающим списком разделов жесткого диска. Выбирается нужный раздел щелчком левой кнопки мыши | Отображается список папок и файлов диска | Отображается список папок и файлов диска | Пройден 
#2U | Проверка отображения содержимого диска, выбранного по умолчанию | Приложение запущено впервые | Отображается список элементов одного из разделов жесткого диска | Отображается список элементов одного из разделов жесткого диска | Пройден
#3U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение содержимого выбранного каталога | Отображается содержимое выбранного каталога | Пройден
#4U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение сообщения об ошибке открытия папки | Отображается сообщение об ошибке | Пройден
#5U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Открытие файла соответсвующей программой | Открытие .pdf в AdobeReader | Пройден
#6U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Сообщение об ошибке открытии файла | Отображается окно с ошибкой | Пройден
#7U | Проверка отображения информации о папке или файле | Нажатие правой кнопки мыши по одному из элементов в списке | Отображение окна с информацией о выбранном элементе | Отображается информация о файле | Пройден
#8U | Проверка операции копирования | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ходом операции | Успешное завершение операции | Пройден
#9U | Проверка операции копирования | Нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#10U | Проверка операции перемещения | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ходом операции | Отображение хода операции и ее завершение | Пройден
#11U | Проверка операции перемещения | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Не отображается окно с ошибкой | Провален
#12U | Проверка операции удаления | Выбор левой кнопкой мыши в одном из списков файла или папки; нажатие кнопки удаление в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ходом операции | Отображение окна с ходом удаления и успешное удаление | Пройден
#13U | Проверка операции удаления | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ифнормацией об ошибке выполнения | Отображение окна с ошибкой | Провален
#14U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Создание нового файла и обновление содержимого каталога | Создан новый файл | Пройден
#15U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Создание нового каталога и обновление содержимого текущего | Создан новый каталог | Пройден
#16U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Появление окна с сообщением о существовании такого файла и запросом ввода нового имени файла | Введено новое имя и создан новый файл | Пройден
#17U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Появление окна с сообщением о существовании такого каталога и запросом ввода нового имени каталога | Введено новое имя и создан новый каталог | Пройден
#18U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне нового имени | Переименование выбранного элемента и обновление содержимого текущего | Введено имя и каталог переименован| Пройден
#19U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне имени, которое совпадает с именем уже существующего элемента | Появление окна с сообщением о существовании такого элемента и запросом ввода нового имени | Повторно введено имя и каталог переименован| Пройден

## Заключение
Тестирование показало общую работоспособность приложения на различных операционных системах, а также при работе с периферийными устройствами. На ОС семейства Linux наблюдается неправильная работа некоторых функций. Также при выполнении некоторых операций отсутствуют сообщения о возникших ошибках. Нефункциональнфе требования выполнены полностью. 