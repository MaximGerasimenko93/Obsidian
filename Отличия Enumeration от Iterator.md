#flashcards
Data: 2023-02-06 13:51
Title: [[Отличия Enumeration от Iterator]]
Alias:
Header:




Body:


Чем отличаются друг от друга интерфейсы `Enumeration` и `Iterator`?
!---
Ответ:
	- С помощью `Enumeration` нельзя добавлять/удалять элементы;
	- В `Iterator` исправлены имена методов для повышения читаемости кода (`Enumeration.hasMoreElements()` соответствует `Iterator.hasNext()`, `Enumeration.nextElement()` соответствует `Iterator.next()` и т.д);
	- `Enumeration` присутствуют в устаревших классах, таких как `Vector`/`Stack`, тогда как `Iterator` есть во всех современных классах-коллекциях.
<!--SR:!2023-03-11,3,150-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
