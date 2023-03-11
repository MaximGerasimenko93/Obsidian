#flashcards
Data: 2023-02-18 10:57
Title: [[Ответственность @EnableTransactionManagement]]
Alias:
Header:



Body:



#Spring 
За что отвечает аннотация @EnableTransactionManagement
!---
Ответ:
	- @EnableTransactionManagement отвечает за регистрацию необходимых компонентов Spring, таких как TransactionInterceptor и советы прокси (proxy advices- набор инструкций, выполняемых на точках среза - Pointcut). 
	- Регистрируемые компоненты помещают перехватчик в стек вызовов при вызове методов @Transactional.
<!--SR:!2023-03-11,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
