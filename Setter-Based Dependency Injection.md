#flashcards #Spring 
Data: 2023-03-11 10:11
Title: [[Setter-Based Dependency Injection]]
Alias:
Header:

Что такое [[Setter-Based Dependency Injection]]?::[[Setter-Based Dependency Injection]] – предполагает, что контейнер вызывает сеттеры класса после вызова конструктора без аргументов или после вызова статического factory метода без аргумента для создания экземпляра bean.
<!--SR:!2023-03-12,1,390-->


Body:



#Spring 
Можно ли комбинировать constructor-based injection с setter-based injection?
!---
Ответ:
	- Да, можно комбинировать эти типы внедрения зависимостей для создания для одного и того же bean.
	- Документация Spring рекомендует использовать конструктор для создания обязательных зависимостей, а сеттер для дополнительных.




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
