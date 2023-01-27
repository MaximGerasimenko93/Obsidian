#flashcards
Data: 2023-01-26 20:53
Title: [[System class loader]]
Alias:
Header:

Что такое [[System class loader]]?::[[System class loader]] – это системный загрузчик.
<!--SR:!2023-01-28,1,130-->



Body:

Что делает system class loader?
!---
Ответ:
- Загружает код, найденный в `java.class.path`, который сопоставляется с переменной среды `CLASSPATH`. Это реализуется классом `sun.misc.Launcher$AppClassLoader`.
- Реализован уже на уровне JRE
- 
<!--SR:!2023-01-28,1,130-->




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] [Загрузка классов в Java. Теория](https://habr.com/ru/post/103830/)
- [ ] []()
