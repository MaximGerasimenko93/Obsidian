#flashcards #Spring 
Data: 2023-03-02 20:22
Title: [[SecurityContext]]
Alias:
Header:

Что такое [[SecurityContext]]?::[[SecurityContext]] – это интерфейс, отражающий контекст безопасности для текущего потока. Является контейнером для объекта типа `Authentication`. (Аналог – `ApplicationContext`, в котором лежат бины).
<!--SR:!2023-03-14,3,350-->


Body:



#Spring 
Сколько экземпляров `SecurityContext` создаются на поток?
!---
Ответ:
	- По умолчанию на каждый поток создается один `SecurityContext`.
<!--SR:!2023-03-11,3,260-->



#Spring 
Где хранятся `SecurityContext` ?
!---
Ответ:
	- `SecurityContext` хранятся в `SecurityContextHolder`.
<!--SR:!2023-03-11,3,280-->



#Spring 
Какие методы имеет `SecurityContext`?
!---
Ответ:
	- `getAuthentication()` и `setAuthentication(Authentication authentication)`.
<!--SR:!2023-03-13,3,200-->


Главы:
- [[SecurityContextHolder]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
