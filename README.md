# TimeLeaksTracker

TimeTracker - это мини-приложение для отслеживания временных затрат на различные виды деятельности (или безделия :)
Также можно записывать расходы любых других ресурсов с указанием количества и временной меткой, составлять списки покупки, списки дел и т.д.

# UserStory
 
Заходя в приложение впервые за текущий день, пользователь видит заполнненный список действий предыдущего дня, либо любой другой список, который был открыт последним. 

Пользователь нажимает кнопку "новый день" на тулбаре. При этом создается новый пустой список, а название в тулбаре меняется на текущую дату.

Далее рабобта в приложении может просиходить происходдит по двух различным сценриям:

  # I. Первичное "беглое" заполнение. 
В течение дня пользователь заполняет список "на бегу", с опечатками и с весьма приблизительными значениями графы "количество". У пользователя зачастую есть всего несколько секунд на бегу или за рулем, чтобы воспользоваться приложением. Для ускорения процеса используется автозаполнение.

Пример заполнения на этом этапе:
    
**     #31/06/22
* Сон, ч ----------- 5
* Работа, ч -------- 6
* Продууты, р ---- 567
**

	
  # II. Исправление, уточнение, создание вложенных списков
Когда у пользователя выдалось побольше свободного времени, он заходит в приложение и редактирует "беглый" список, заполненный на Этапе I, уточняя название, значения поля "количество", а также создавая на основе данной записи создать вложенный списокю

по правой кнопке мыши (или удерживая тап) выпадает меню:
 - редактировать ()
 - создать группу отсюда
 - удалить (ShowAlert)

    
    # Отдельно следует выделить режим анализа.
    Для анализа существующих записей нужен отдельный экран, в котором предумотрено формирование различных отчётов, а также их экспорт.
    
    Формы отчётов:
    - Недельный /месячный /квартальный /произвольный
    - Полный /по выбранным категориям 
    - по проектам ?
