# Динамический адаптив (Dynamic Adapt)
JS функция для комфортной адаптивной верстки. Позволяет "перебрасывать" объекты в DOM в зависимости от потребностей при адаптивной верстке.

# Применение.
Для перещаемого объекта пишем атрибут - `data-da` и указываем значения, например 

# Пример

`data-da="class_name,2,992"`

class_name (обязательно) - имя класса элемента в который нужно переместить объект. Если класс не уникален, объект переместится в первый элемент.
2 (не обязателно, по умолчанию last) - позиция на которую нужно переместить объект внутри родителя class_name. Можно указать first (в начало блока) или last (в конец блока)
992 (не обязателно, по умолчанию 767) - брейкпоинт при котором перемещать объект.

