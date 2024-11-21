# 1Chomeworks
Здесь выкладываю свои домашние задания по курсу 1С разработчик: с нуля до Middle от Нетологии
************************************************************************************************************************************************************************************
Задача "Выгрузка и загрузка информационной базы и конфигурации" (файл Домашнее задание+.dt).

Описание задачи:
Следует загрузить демонстрационную базу, загрузить ее конфигурацию в пустую информационную базу и выгрузить пустую информационную базу с демо-конфигурацией.

Требования к результату:
Результат - файл выгрузки информационной базы с расширением .dt, содержащий конфигурацию демобазы, но без ее данных.
************************************************************************************************************************************************************************************
Задача 1 "Основные свойства конфигурации" (файл Задание 1.cf).

Описание задачи:
Нужно создать с нуля пустую конфигурацию, заполнить ее имя и основные свойства.

Требования к результату:
Результат - файл .cf конфигурации с заполненным именем и несколькими основными свойствами.
************************************************************************************************************************************************************************************
Задача 2 "Сравнение и объединение конфигураций"  (файл Задание 2.cf).

Описание задачи:
Нужно объединить конфигурацию демобазы с конфигурацией из файла, взяв из файла новый справочник Студенты, удалив неиспользуемый справочник УдалитьПользователи и сохранив неизменным справочник Лекции.

Требования к результату:
Результат - файл .cf конфигурации, содержащий:

-справочник Студенты.

-табличную часть ВыполнениеСтудентами справочника Задания. В форме элемента справочника Лекции должна остаться закладка Задания. Справочник УдалитьПользователи должен отсутствовать.
************************************************************************************************************************************************************************************
Задача 3 "Проверка конфигурации"  (файл Задание 3.cf).

Описание задачи:
Требуется проверить демо-конфигурацию на предмет двух специально привнесенных ошибок и исправить их согласно тексту комментариев рядом с ошибками.

Требования к результату:
Результат - файл .cf конфигурации, не выдающий ошибок проверки.
************************************************************************************************************************************************************************************
Задача 4 "Обновление конфигурации"  (файл Задание 4.cf).

Описание задачи:
Нужно обновить конфигурацию демобазы до версии 1.0.0.2 файлом обновления.

Требования к результату:
Результат - файл конфигурации демобазы (.cf), обновленный до версии 1.0.0.2, в котором есть заставка и удален справочник УдалитьПользователи.
************************************************************************************************************************************************************************************
Задание к занятию "Дерево метаданных" (файл Задание 5.cf).

Требования к результату:
Результатом выполнения всех трех задач должен быть общий файл .CF конфигурации, содержащий все, созданное в ходе выполнения задач. Для выполнения всех трех задач, используйте базу с конфигурацией УправлениеИТФирмой, созданную Вами ранее
************************************************************************************************************************************************************************************
Задача 1 "Создание справочника Сотрудники"

Описание задачи:
Нужно создать справочник Сотрудники и функциональную опцию ВестиРасчетЗарплаты, включив в ее состав реквизиты сотрудников, относящиеся к зарплате.

Требования к результату:
Результат - файл .CF конфигурации, содержащий справочник Сотрудники с реквизитами Email, Телефон, Оклад и СтавкаЧаса, и функциональную опцию, в состав которой включены реквизиты, относящиеся к расчету зарплаты.
************************************************************************************************************************************************************************************
Задача 2 "Создание справочника Контрагенты"

Описание задачи:
Нужно создать перечисление ЮридическоеФизическоеЛицо и справочник Контрагенты, использующий его.

Требования к результату:
Результат - файл .CF конфигурации, содержащий перечисление ЮридическоеФизическоеЛицо и справочник Контрагенты с реквизитами ПолноеНаименование, ЮридическийАдрес, ПочтовыйАдрес, ИНН, КПП и ЮридическоеФизическоеЛицо.
************************************************************************************************************************************************************************************
Задача 3 "Создание подсистемы Справочники"

Описание задачи:
Нужно создать подсистему Справочники, включающую справочники Сотрудники и Контрагенты.

Требования к результату:
Результат - файл .CF конфигурации, содержащий подсистему Справочники со справочниками Контрагенты и Сотрудники.
************************************************************************************************************************************************************************************
Задача "Публикация информационной базы на веб-сервере" (файл Задание 6 Снимок экрана.png).

Описание задачи:
Нужно опубликовать учебную информационную базу на веб-сервере, установив его, если необходимо.

Требования к результату:
Результат - снимок экрана, в котором должно быть окно браузера, а в нем - одна из учебных информационных баз с открытым окном "О программе".
************************************************************************************************************************************************************************************
Задача 1 "Создание ролей и пользователей" (файл ИБ с пользователями и ролями.dt).

Описание задачи:
Нужно создать роли ПолныеПрава, БазовыеПрава, ДобавлениеИзменениеКонтрагентов и ДобавлениеИзменениеСотрудников и назначить их четырем пользователям.

Требования к результату:
Результат - выгрузка (.dt) информационной базы, в которой есть роли ПолныеПрава и БазовыеПрава, а также:

пользователь Администратор с полными правами;
пользователь с базовыми правами;
пользователь с базовыми правами и правом на редактирование контрагентов;
пользователь с базовыми правами и правом на редактирование сотрудников;
************************************************************************************************************************************************************************************
Задача 2 "Поиск ошибки с помощью точки останова" (файл Задание отладки фоновой ошибки (точка останова).cf).

Описание задачи:
Нужно найти в учебной демобазе и исправить специально привнесенную ошибку с помощью остановки по ошибке.

Требования к результату:
Результат - файл .CF конфигурации, в котором исправлена ошибка, возникавшая при попытке записать блок.
************************************************************************************************************************************************************************************
Задача 3 "Поиск ошибки с помощью журнала регистрации" (файл Задание поиск и устранение ошибки (журнал регистрации).cf).

Описание задачи:
Нужно найти в учебной демобазе и исправить специально привнесенную ошибку с помощью журнала регистрации.

Требования к результату:
Результат - файл .CF конфигурации, в котором исправлена ошибка, возникавшая при работе фонового задания.
************************************************************************************************************************************************************************************
Задача 1 "Создание внешней обработки"

Описание задачи:
Создать внешнюю обработку Калькулятор с четырьмя арифметическими действиями

Требования к результату:
Результат - файл внешней обработки (.epf), в которой будут:

два реквизита формы Результат и Значение;
два соответствующих им поля ввода;
четыре команды: Сложить, Вычесть, Разделить и Умножить и четыре кнопки.
Команды должны проводить соответствующее арифметическое действие, помещая его результатат в реквизит Результат.
************************************************************************************************************************************************************************************
Задача 2 "Создание внешнего отчета"

Описание задачи:
Создать внешний отчет "Лекции", который выведет все лекции курса в виде детальных записей. 

Требования к результату:
Результат - файл внешнего отчета (*.erf) с единственным набором данных, содержащим поля:

Наименование
Дата
Модуль
Отчет должен выводить детальные записи с колонками "Наименование", "Дата" и "Модуль".
************************************************************************************************************************************************************************************
