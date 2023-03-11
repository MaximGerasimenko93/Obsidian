#flashcards #Spring 
Data: 2023-02-13 13:40
Title: [[ApplicationContext]]
Alias:
Header:

Что такое [[ApplicationContext]]?::[[ApplicationContext]] – это интерфейс, реализации которого создают компоненты приложения, связывает их вместе, настраивает и управляет ими от создания до момента уничтожения. Т.е. обеспечивает жизненный цикл. Компоненты после создания хранятся в контексте и называются бинами ([[Bean]]). В упрощенном виде контекст можно представить, как Map, где ключом является id бина. Является наследником [[BeanFactory]]
<!--SR:!2023-03-12,1,130-->



Body:



#Spring 
Что делает ApplicationContext?
!---
Ответ:
	- ApplicationContext загружает бины, связывает их вместе и конфигурирует их определённым образом.
<!--SR:!2023-03-12,2,130-->


#Spring 
Что представляет ApplicationContext?
!---
Ответ:
	- Интерфейс ApplicationContext представляет IoC Container.
<!--SR:!2023-03-12,2,130-->




Главы:
- [[Bean]]
- [[Дополнительный функционал ApplicationContext]]
- [[Основные этапы поднятия ApplicationContext]]
- [[Реализация ApplicationContext]]
- [[Отличия ApplicationContext от BeanFactory]]


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
