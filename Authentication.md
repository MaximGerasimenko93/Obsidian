#flashcards #Spring 
Data: 2023-03-02 20:43
Title: [[Authentication]]
Alias:
Header:

Что такое [[Authentication]]?::[[Authentication]] – это объект, отражающий информацию о текущем пользователе и его привилегиях.
<!--SR:!2023-03-13,3,290-->




Body:



#Spring 
Для чего Spring Security использует `Authentication`?
!---
Ответ:
	- Вся работа Spring Security будет заключаться в том, что различные фильтры и обработчики будут брать и класть объект `Authentication` для каждого посетителя.
<!--SR:!2023-03-11,3,220-->



#Spring 
Какой командой можно достать `Authentication`?
!---
Ответ:
	- Объект `Authentication` можно достать в Spring MVC контроллере командой `SecurityContextHolder.getContext().getAuthentication()`.
<!--SR:!2023-03-11,1,200-->



#Spring
Какую реализацию имеет `Authentication` по умолчанию?
!---
Ответ:
	- `Authentication` имеет реализацию по умолчанию – класс `UsernamePasswordAuthenticationToken`, предназначенный для хранения логина, пароля и коллекции `Authorities`.
<!--SR:!2023-03-11,1,200-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
