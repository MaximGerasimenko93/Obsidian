#flashcards #Spring 
Data: 2023-03-11 10:38
Title: [[Factory method injection]]
Alias:
Header:

Что такое [[Factory method injection]]?::[[Factory method injection]] – это фабричный метод, который вызывает зависимость в bean.
<!--SR:!2023-03-12,1,390-->


Body:

#Spring 
Как выглядит стандартная реализация фабричного метода?
!---
Ответ:
	- Стандартно выполнение фабричного метода означает создание метода экземпляра класса, который возвращает нам желаем bean. Можно создать нужный bean с аргументами или без.


#Spring 
Возможно ли использовать статический метод в качестве фабричного?
!---
Ответ:
	- Да, можно. Хотя предпочтительно использовать фабричный метод в экземпляре класса.
	- Статический метод в качестве фабричного полезен в случае, когда статические методы производят компоненты bean.



Главы:
-


Sources:
- [ ] [Creating Spring Beans Through Factory Methods](https://www.baeldung.com/spring-beans-factory-methods)
- [ ] [Dependency Injection with Factory Method in Spring](https://www.javatpoint.com/dependency-injection-with-factory-method)
- [ ] []()
