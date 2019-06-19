# 1. Объект тестирования
Продукт BagManager представляет собой типичный файловый менеджер. Приложение взаимодействует с файловой системой компьютера, поэтому к нему предъявляются серьезные требования качества. 

Приложение делится на три основных компонента: подсистема отображения графичческого пользовательского интерфейса (GUI), контроллер GUI, подсистема контроля выполнения операций с файловой системой.

Атрибуты качества для продукта: доступность - приложение доступно к использованию на протяжении любого времени с момента запуска (более 5 мин); безопасность использования - невозможность совершения операций со скрытыми или системными файлами; простота совершения операций - количество совершаемых действий для выполнения операции с файловой системой не более чем, при выполнении той же операции стандартными средствами ОС.
# 2. Аспекты тестирования
Use case тестирование - тестирование выполнения основных сценариев использования приложения.

Тестирование кроссплатформенности - тестирование функционала приложения на операционных системах семейства Linux и Windows.

Тестирование работы с периферийными устройствами (ПУ) - тестирование функционала приложения при взаимодействии с ПУ.
# 3. Подходы к тестированию
Для тестирования разрабатывамого продукта применятеся системный подход, т.е. проверка функциональных и нефункциональных требований для системы  в целом без использования автоматических средств тестирования (ручное тестирование). Тестирование осуществляется на основе сценариев использования
# 4. Тестовые сценарии
## UseCases
Идентификатор  | Назначение | Сценарий | Ожидаемый результат
--|--|--|--
#1U | Проверка отображения содержимого  выбранного диска | Активируется элемент ComboBox c выпадающим списком разделов жесткого диска. Выбирается нужный раздел щелчком левой кнопки мыши | Отображается список папок и файлов диска
#2U | Проверка отображения содержимого диска, выбранного по умолчанию | Приложение запущено впервые | Отображается список элементов одного из разделов жесткого диска
#3U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение содержимого выбранного каталога
#4U | Проверка отображения содержимого каталога | Двойное нажатие левой кнопки мыши по одной из папок в списке | Отображение сообщения об ошибке открытия папки
#5U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Открытие файла соответсвующей программой
#6U | Проверка возможности открытия файла из приложения средствами ОС | Двойное нажатие левой кнопки мыши по одному из файлов в списке | Сообщение об ошибке открыти файла
#7U | Проверка отображения информации о папке или файле | Нажатие правой кнопки мыши по одному из элементов в списке | Отображение окна с информацией о выбранном элементе
#8U | Проверка операции копирования | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ходом операции
#9U | Проверка операции копирования | Нажатие кнопки копирование в соответствии со списком, в котором выбран исходный копируемый элемент | Отображение окна с ифнормацией об ошибке выполнения
#10U | Проверка операции перемещения | Выбор левой кнопкой мыши в одном из списков файла или папки; выбор нужной папки в другом списке; нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ходом операции
#11U | Проверка операции перемещения | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный перемещаемый элемент | Отображение окна с ифнормацией об ошибке выполнения
#12U | Проверка операции удаления | Выбор левой кнопкой мыши в одном из списков файла или папки; нажатие кнопки удаление в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ходом операции
#13U | Проверка операции удаления | Нажатие кнопки перемещение в соответствии со списком, в котором выбран исходный удаляемый элемент | Отображение окна с ифнормацией об ошибке выполнения
#14U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Создание нового файла и обновление содержимого каталога
#15U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Создание нового каталога и обновление содержимого текущего
#16U | Проверка операции создания | Выбор каталога, в котором создается новый файл; нажатие кнопки создать в соответствии со списком, в котором выбран исходный файл; ввод в появившемся окне имени с расширением | Появление окна с сообщением о существовании такого файла и запросом ввода нового имени файла
#17U | Проверка операции создания | Выбор каталога, в котором создается новый каталог; нажатие кнопки создать в соответствии со списком, в котором выбран исходный каталог; ввод в появившемся окне имени без расширения | Появление окна с сообщением о существовании такого каталога и запросом ввода нового имени каталога
#18U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне нового имени | Переименование выбранного элемента и обновление содержимого текущего
#19U | Проверка операции переименования | Выбор файла или каталога для переименования; нажатие кнопки переименовать в соответствии со списком, в котором выбран исходный элемент; ввод в появившемся окне имени, которое совпадает с именем уже существующего элемента | Появление окна с сообщением о существовании такого элемента и запросом ввода нового имени
##Нефункциональные требования
#1NF | Проверка доступности приложения | Запуск приложения. Ожидание на протяжении 5мин. | Приложение работает по истечении заданного времени
#2NF | Проверка безопасности использования | Выбрать системный файл. Нажать кнопку удалить | Сообщение об ошибке удаления файла
#3NF | Проверка простоты совершения операций | Выбор исходного файла для копирования. Выбор путь назначения. Нажать кнопку копирование. Подсчитать количество совершенных действий. Произвести операцию копирования стандартными средствами ОС. Подсчитать количество действий | Количество действий, затрачиваемых на операцию копирования меньше, чем стандартными средствами ОС. 

