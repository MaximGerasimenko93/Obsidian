#flashcards
Data: 2023-02-13 14:47
Title: [[Основные этапы поднятия ApplicationContext]]
Alias:
Header:




Body:


#Spring 
Назовите основные этапы поднятия ApplicationContext.
!---
Ответ:
	- 1 этап: Парсирование конфигурации (xml, groovy, JavaConfig и пр.) и создание всех `BeanDefinition` (`AnnotatedBeanDefinitionReader`, `BeanDefinitionReader`, `ClassPathBeanDefinitionScanner`)
	- 2 этап: Настройка созданных `BeanDefinition (BeanFactoryPostProcessor)`
	- 3 этап: Создание кастомных `FactoryBean (FactoryBean<T>)`
	- 4 этап: BeanFactory создает экземпляры бинов, при необходимости делегируя создание `FactoryBean (BeanFactory)`
	- 5 этап: Настройка созданных бинов (BeanPostProcessor)
<!--SR:!2023-03-11,1,130-->



Главы:
-


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit)
- [ ] []()
- [ ] []()
