#flashcards
Data: 2023-02-13 17:56
Title: [[Частые аннотации Spring]]
Alias:
Header:




Body:




#Spring 
Какие аннотации часто используются в Spring?
!---
Ответ:
	- `@Autowired` – используется для автоматического связывания зависимостей в spring beans.
	-   `@Bean` – В классах конфигурации Spring, @Bean используется для для непосредственного создания бина.
	-   `@Controller` – класс фронт контроллера в проекте Spring MVC.
	-   `@ConditionalOn*` – Создает бин если выполняется условие. `Condition` – функциональный интерфейс, который содержит метод boolean matches(ConditionContext context, AnnotatedTypeMetadata metadata)
	-   `@Sheduler` – Таймер. Раз в сколько-то секунд обрабатывать.
	-   `@Resource` – Java аннотация, которой можно внедрить зависимость.
	-   `@Requared` – применяется к методам-сеттерам и означает, что значение метода должно быть установлено в XML-файле. Если этого не будет сделано, то мы получим BeanInitializationException.
	-   `@RequestMapping` – используется для мапинга (связывания) с URL для всего класса или для конкретного метода обработчика.
	-   `@ResponseBody` – позволяет отправлять Object в ответе. Обычно используется для отправки данных формата XML или JSON.
	-   `@ResponseEntity` – используется для формирования ответа HTTP с пользовательскими параметрами (заголовки, http-код и т.д.). ResponseEntity необходим, только если мы хотим кастомизировать ответ, добавив к нему статус ответа. Во всех остальных случаях будем использовать @ResponseBody.
	-   `@PathVariable` – задает динамический маппинг значений из URI внутри аргументов метода обработчика, т.е. позволяет вводить в URI переменную пути в качестве параметра
	-   `@Qualifier` – используется совместно с @Autowired для уточнения данных связывания, когда возможны коллизии (например одинаковых имен\типов).
	-   `@Service` – указывает что класс осуществляет сервисные функции.
	-   `@Scope` – указывает scope у spring bean.
	-   `@Configuration`, `@ComponentScan` и `@Bean` – для java based configurations.
	-   `AspectJ` аннотации для настройки aspects и advices, `@Aspect`, `@Before`, `@After`, `@Around`, `@Pointcut` и др.
	-   `@PageableDefault` – устанавливает значение по умолчанию для параметра разбиения на страницы
<!--SR:!2023-03-12,2,130-->




Главы:
- [[Аннотации @Qualifier и @Primary]]
- [[Аннотации @Bean и @Component]]
- [[Аннотации @Component, @Service и @Repository]]
- [[Аннотации @Controller и @RestController]]
- [[Аннотации @ResponseBody и @ResponseEntity]]
- [[Аннотация @EnableTransactionManagement]]


Sources:
- [ ] [Spring вопросы-ответы](https://docs.google.com/document/d/1eFbKDhPfud_Kj07jHhj-OmZuEfHYWe4HaLUW4pRkZ9U/edit#heading=h.26f0p2oxn1f9)
- [ ] []()
- [ ] []()
