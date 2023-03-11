#flashcards #Spring 
Data: 2023-03-02 20:52
Title: [[Principal]]
Alias:
Header:

Что такое [[Principal]]?::[[Principal]] – это интерфейс из пакета `java.security`, отражающий учетную запись пользователя. В терминах логин-пароль это логин.
<!--SR:!2023-03-14,3,250-->




Body:



#Spring 
Как реализуется `Principal`?
!---
Ответ:
	- В интерфейсе `Authentication` есть метод `getPrincipal()`, возвращающий `Object`. При аутентификации с использованием имени пользователя/пароля `Principal` реализуется объектом типа `UserDetails`.
<!--SR:!2023-03-11,1,188-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
