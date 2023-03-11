#flashcards #Spring 
Data: 2023-02-13 14:51
Title: [[BeanFactory]]
Alias:
Header:

Что такое [[BeanFactory]]?::[[BeanFactory]] – это фактический контейнер, который создает, настраивает и управляет рядом bean-компонентов. Это Корневой интерфейс для доступа к контейнеру Spring bean. Отвечает за содание бинов на основе BeanDefinition при этом, если нужно, делегирует это кастомным FactoryBean.
<!--SR:!2023-03-12,1,130-->



Body:

#Spring 
Какие зависимости есть у BeanFactory?
!---
Ответ:
	- Эти бины обычно взаимодействуют друг с другом и, таким образом, имеют зависимости между собой.
	- Эти зависимости отражены в данных конфигурации, используемых BeanFactory.
	- BeanFactory обычно используется тогда, когда ресурсы ограничены (мобильные устройства).
	- Поэтому, если ресурсы не сильно ограничены, то лучше использовать ApplicationContext.
<!--SR:!2023-03-11,1,130-->




Главы:
- [[Отличия ApplicationContext от BeanFactory]]


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
