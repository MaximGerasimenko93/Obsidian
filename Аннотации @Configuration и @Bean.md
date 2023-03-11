#flashcards
Data: 2023-03-10 21:07
Title: [[Аннотации @Configuration и @Bean]]
Alias:
Header:




Body:



#Spring 
Для чего используют аннотации `@Configuration` и `@Bean`?
!---
Ответ:
	- `@Configuration` указывает, что класс является источником bean definition
	- `@Bean` используется для явного определения `bean`. Если не указывать пользовательское имя у `bean`, то по умолчанию он примет имя метода. 
	- Если `bean` по умолчанию `singletone`, то Spring проверяет существует ли уже экземпляр bean. Если его нет, то создает новый.
	- В случае `prototype`, контейнер возвращает новый `bean` при каждом вызове метода.
<!--SR:!2023-03-11,1,230-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
