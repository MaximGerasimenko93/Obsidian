#flashcards 
Data: 2022-04-28 16:47
Title: [[Dependency Inversion Principle]]
Alias:
	- DIP
	- Dependency Inversion Principle
	- Принцип инверсии зависимостей
Header:
	- Что такое [[Dependency Inversion Principle]]?::Принцип инверсии зависимостей - это принцип проектирования, который говорит, что классы должны зависеть от высокоуровневых абстракций.. Нет зависимости на что-то конкретное. Высокоуровневые абстракции не должны зависеть от низкоуровневых абстракций, а должны завxисеть только от интерфейса. В соответствии с ним: 1) Модули верхних уровней не должны зависеть от модулей нижних уровней; 2) Оба типа модулей должны зависеть от абстракций; 3) Абстракции не должны зависеть от деталей. Детали должны зависеть от абстракций. Не соблюдение правила вырождается в Закон протекающих абстракций. Модуль – логически взаимосвязанная совокупность функциональных элементов. Дополнение: Устойчивость к изменениям.
<!--SR:!2023-03-12,1,130-->

Body:



Главы:
- [[Dependency Injection]]
- [[Inversion of Control]]

Sources:
1) [# DI vs. DIP vs. IoC](http://sergeyteplyakov.blogspot.com/2014/11/di-vs-dip-vs-ioc.html)
2) [# Understanding the Use of Interface and Abstract Classes](https://betterprogramming.pub/understanding-use-of-interface-and-abstract-class-9a82f5f15837)
3) [# Разбираемся с SOLID: Инверсия зависимостей](https://habr.com/ru/post/313796/)
4) 
