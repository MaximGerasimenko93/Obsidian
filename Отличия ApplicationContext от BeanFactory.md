#flashcards
Data: 2023-02-25 15:30
Title: [[Отличия ApplicationContext от BeanFactory]]
Alias:
Header:




Body:


#Spring 
Чем отличаются [[ApplicationContext]] от [[BeanFactory]]?
!---
Ответ:
	- [[ApplicationContext]] расширяет возможности [[BeanFactory]]
	- [[BeanFactory]] загружает бины по требованию. [[ApplicationContext]] загружает все бины при запуске.
	- [[BeanFactory]] поддерживает только две skope – Singleton и Prototype . [[ApplicationContext]] поддерживает  все типы skope bean-компонентов
<!--SR:!2023-03-11,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
