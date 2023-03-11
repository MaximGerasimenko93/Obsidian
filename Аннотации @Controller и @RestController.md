Title: [[Аннотации @Controller и @RestController]]
Alias:
Header:





Body:




#Spring 
Для чего используют аннотации `@Controller` и `@RestController`?
!---
Ответ:
	- @Controller помечает класс как контроллер HTTP запросов. `@Controller` обычно используется в сочетании с аннотацией `@RequestMapping`, используемой в методах обработки запросов.
	- В Spring 4.0 была представлена аннотация `@RestController`. Применив ее к контроллеру автоматически добавляются аннотации `@Controller`, а также `@ResponseBody` применяется ко всем методам.
	- Аннотация `@ResponseBody` сообщает контроллеру, что возвращаемый объект автоматически сериализуется в JSON и передается обратно в объект HttpResponse.
	- `@RestController = @Controller + @ResponseBody`.
	- `@RestController` превращает помеченный класс в Spring-бин. Этот бин для конвертации входящих/исходящих данных использует Jackson message converter. Как правило целевые данные представлены в json или xml.
<!--SR:!2023-03-11,1,130-->







Главы:
-


Sources:
- [ ] []()
- [ ] []()
- [ ] []()