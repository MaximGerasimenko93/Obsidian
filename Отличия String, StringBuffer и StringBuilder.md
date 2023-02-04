#flashcards
Data: 2023-02-04 17:05
Title: [[Отличия String, StringBuffer и StringBuilder]]
Alias:
Header:




Body:


Назовите отличия между `String`, `StringBuilder` и `StringBuffer`.
!---
Ответ:
	- Класс `String` является неизменяемым (_immutable_) – модифицировать объект такого класса нельзя, можно лишь заменить его созданием нового экземпляра.
	- Класс `StringBuffer` изменяемый – использовать `StringBuffer` следует тогда, когда необходимо часто модифицировать содержимое.
	- Класс `StringBuilder` был добавлен в Java 5 и он во всем идентичен классу `StringBuffer` за исключением того, что он не синхронизирован и поэтому его методы выполняются значительно быстрей.




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
