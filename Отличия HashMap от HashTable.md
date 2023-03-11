#flashcards
Data: 2023-02-07 11:56
Title: [[Отличия HashMap от HashTable]]
Alias:
Header:




Body:



#Collections 
Чем отличаются `HashMap` и `HashTable`?
!---
Ответ:
	- Методы класса `Hashtable` синхронизированы, что приводит к снижению производительности, а `HashMap` - нет.
	- `HashTable` не может содержать элементы `null`. `HashMap` может содержать один ключ `null` и любое количество значений `null`.
	- `Iterator` у `HashMap`, в отличие от `Enumeration` у `HashTable`, работает по принципу "fail-fast" (выдает исключение при любой несогласованности данных).
	- `Hashtable` это устаревший класс и его использование не рекомендовано.
<!--SR:!2023-03-14,3,170-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
