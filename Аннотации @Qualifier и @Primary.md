#flashcards
Data: 2023-02-13 17:45
Title: [[Аннотации @Qualifier и @Primary]]
Alias:
Header:




Body:



#Spring 
Когда применяются аннотации `@Qualifier` и `@Primary`?
!---
Ответ:
	- Если есть два одинаковых бина (по типу и имени) спринг не знает какой именно использовать и выдаёт exeption.
	- `@Primary` указывает какой бин предпочтительнее использовать.
	- `@Qualifier` используется, когда для работы приложения нужны эти два бина. Над каждым надо поставить эту аннотацию, а затем задать имя для идентификации этих бинов.
<!--SR:!2023-03-12,2,150-->




Главы:
-


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
