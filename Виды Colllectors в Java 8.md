#flashcards
Data: 2023-02-10 18:27
Title: [[Виды Colllectors в Java 8]]
Alias:
Header:




Body:



#Java8 
Какие `Collectors` распространены в Java 8?
!---
Ответ:
	- `toList()`, `toCollection()`, `toSet()` - представляют стрим в виде списка, коллекции или множества
	-   `toConcurrentMap()`, `toMap()` - позволяют преобразовать стрим в `Map`
	-   `averagingInt()`, `averagingDouble()`, `averagingLong()` - возвращают среднее значение
	-   `summingInt()`, `summingDouble()`, `summingLong()` - возвращает сумму
	-   `summarizingInt()`, `summarizingDouble()`, `summarizingLong()` - возвращают `SummaryStatistics` с разными агрегатными значениями
	-   `partitioningBy()` - разделяет коллекцию на две части по соответствию условию и возвращает их как `Map<Boolean, List>`
	-   `groupingBy()` - разделяет коллекцию на несколько частей и возвращает `Map<N, List<T>>`
	-   `mapping()` - дополнительные преобразования значений для сложных `Collector`-ов
	- `Collector.of()` – создание собственного коллектора
<!--SR:!2023-03-11,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
