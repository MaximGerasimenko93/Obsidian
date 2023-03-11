#flashcards
Data: 2023-02-08 12:11
Title: [[Отличия LinkedHashSet и HashSet]]
Alias:
Header:




Body:



#Collections 
Чем отличаются `LinkedHashSet` и `HashSet`
!---
Ответ:
	- `LinkedHashSet` отличается от `HashSet` только тем, что в его основе лежит `LinkedHashMap` вместо `HashMap`.
	- Благодаря этому порядок элементов при обходе коллекции является идентичным порядку добавления элементов (insertion-order).
	- При добавлении элемента, который уже присутствует в `LinkedHashSet` (т.е. с одинаковым ключом), порядок обхода элементов не изменяется.
<!--SR:!2023-03-14,3,150-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
