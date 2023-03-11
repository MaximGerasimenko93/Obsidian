#flashcards #Spring 
Data: 2023-02-18 11:00
Title: [[Жизненный цикл Bean]]
Alias:
Header:

Что такое [[Жизненный цикл Bean]]?::[[Жизненный цикл Bean]] – это время существования класса.
<!--SR:!2023-03-11,2,170-->



Body:



#Spring 
Опишите весь жизненный цикл бинов.
!---
Ответ:
	-   Загрузка описаний бинов, создание графа зависимостей(между бинами)
    -   Создание и запуск BeanFactoryPostProcessors
    -   Создание бинов
    -   Spring внедряет значения и зависимости в свойства бина
    -   Если бин реализует метод setBeanName() из интерфейса NameBeanAware, то ID бина передается в метод
    -   Если бин реализует BeanFactoryAware, то Spring устанавливает ссылку на bean factory через setBeanFactory() из этого интерфейса.
    -   Если бин реализует интерфейс ApplicationContextAware, то Spring устанавливает ссылку на ApplicationContext через setApplicationContext().
    -   BeanPostProcessor это специальный интерфейс, и Spring позволяет бинам имплементировать этот интерфейс. Реализуя метод postProcessBeforeInitialization(), можно изменить экземпляр бина перед его(бина) инициализацией(установка свойств и т.п.)
    -   Если определены методы обратного вызова, то Spring вызывает их. Например, это метод, аннотированный @PostConstruct или метод initMethod из аннотации @Bean.
    -   Теперь бин готов к использованию. Его можно получить с помощью метода ApplicationContext#getBean().
    -   После того как контекст будет закрыт(метод close() из ApplicationContext), бин уничтожается.
    -   Если в бине есть метод, аннотированный @PreDestroy, то перед уничтожением вызовется этот метод. Если бин имплементирует DisposibleBean, то Spring вызовет метод destroy(), чтобы очистить ресурсы или убить процессы в приложении. Если в аннотации @Bean определен метод destroyMethod, то вызовется и он.
<!--SR:!2023-03-11,1,130-->





Главы:
- [[Интерфейс BeanPostProcessor]]
- [[Bean scopes]]


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
