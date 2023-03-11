#flashcards 
Data: 2023-02-06 16:54
Title: [[ConcurrentModificationException]]
Alias:
Header:




Body:


#Collections 
Как избежать `ConcurrentModificationException`?
!---
Ответ:
	- Попробовать подобрать или реализовать самостоятельно другой итератор, работающий по принципу fail-safe.
	- Использовать `ConcurrentHashMap` и `CopyOnWriteArrayList`.
	- Преобразовать список в массив и перебирать массив.
	- Блокировать изменения списка на время перебора с помощью блока `synchronized`.
	- Отрицательная сторона последних двух вариантов - ухудшение производительности.
<!--SR:!2023-03-12,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
