# Karpov Soft: Form generator #
## Библиотека для программной генерации элементов формы и вывода их на управляемой форме 1С ##

Данная библиотека является попыткой стандартизировать и упростить программную доработку форм.
Библиотека позволяет:
1. Создать новые элементы формы
2. Создавать команды формы
3. Создавать реквизиты формы.

При этом в самом простом случае, достаточно 2-х строк кода, чтобы добавить на форму поле ввода

```
ПолеВвода = КА_ГенерацияЭлементовФормы.ПолеВвода("Объект.Наименование", "ОсновнаяСтраница");
КА_ГенерацияЭлементовФормы.ДобавитьЭлементНаФорму(Форма, ПолеВвода);

```


