#flashcards #Spring 
Data: 2023-03-02 20:01
Title: [[Spring Security]]
Alias:
Header:

Что такое [[Spring Security]]?::[[Spring Security]] – предоставляет широкие возможности для защиты приложения. Кроме стандартных настроек для аутентификации, авторизации и распределения ролей и маппинга доступных страниц, ссылок и т.п., предоставляет защиту от различных вариантов атак
<!--SR:!2023-03-12,3,330-->


Body:


#Spring 
Что представляет из себя Spring Security?
!---
Ответ:
	- Это список фильтров в виде класса `FilterChainProxy`, интегрированного в контейнер сервлетов, и в котором есть поле `List`. Каждый фильтр реализует какой-то механизм безопасности. Важна последовательность фильтров в цепочке.
<!--SR:!2023-03-11,1,220-->




Главы:
- [[Основные классы и интерфейсы Spring Security]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()