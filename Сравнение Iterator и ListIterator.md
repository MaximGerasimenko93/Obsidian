#flashcards 
Data: 2023-02-06 16:51
Title: [[Сравнение Iterator и ListIterator]]
Alias:
Header:




Body:


#Collections 
Сравните `Iterator` и `ListIterator`.
!---
Ответ:
	-   `ListIterator` расширяет интерфейс `Iterator`
	-   `ListIterator` может быть использован только для перебора элементов коллекции `List`;
	-   `Iterator` позволяет перебирать элементы только в одном направлении, при помощи метода `next()`. Тогда как `ListIterator` позволяет перебирать список в обоих направлениях, при помощи методов `next()` и `previous()`;
	-   `ListIterator` не указывает на конкретный элемент: его текущая позиция располагается между элементами, которые возвращают методы `previous()` и `next()`.
	-   При помощи `ListIterator` вы можете модифицировать список, добавляя/удаляя элементы с помощью методов `add()` и `remove()`. `Iterator` не поддерживает данного функционала.
<!--SR:!2023-03-12,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
