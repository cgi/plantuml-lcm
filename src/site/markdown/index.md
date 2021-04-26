Введение
===

Проект содержит наработки для использования инструмента Plant UML в качестве утилиты для создания Literate Code Maps.
По сути это смесь разных диаграмм (Use Case, Class, Activity) и фрагментов кода основной целью которой является описания порядка обработки в коде того или иного бизнес сценария.

Когда применять
===
Применять данный подход рекомендуется в случае изучения порядока работы нового кода или сложного участка включая в создаваемую диаграмму важные места и пометки.


Использование
===

Подключить файл с помощью ссылки: https://cgi.github.io/plantuml-lcm/lcm.puml

Пример использования
===

````plantuml
@startuml
!include https://cgi.github.io/plantuml-lcm/lcm.puml

class "cls" as cls1 $class_logo("E", "DarkRed", "class assd") {
    +asdf
    #asdf
    $class_section(название\nсекции\nфыва )
    -asfd
}

$newNode( "scenario", "E", "DarkRed", "scenario1", "class12", "ext str") {
}

@end
````