#flashcards #Spring 
Data: 2023-02-18 10:52
Title: [[Аннотация @EnableTransactionManagement]]
Alias:
Header:

Что такое [[Аннотация @EnableTransactionManagement]]?::[[Аннотация @EnableTransactionManagement]] – размещается у класса-конфигурации @Configuration перед включением возможности управления транзакциями.
<!--SR:!2023-03-11,1,130-->



Body:

#Spring 
Что означает аннотация @EnableTransactionManagement?
!---
Ответ:
	- Аннотация @EnableTransactionManagement означает, что классы, помеченные @Transactional, должны быть обернуты аспектом транзакций.
	- Однако, если мы используем Spring Boot и имеем зависимости spring-data-* или spring-tx, то управление транзакциями будет включено по умолчанию.
<!--SR:!2023-03-11,1,130-->




Главы:
- [[Ответственность @EnableTransactionManagement]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
