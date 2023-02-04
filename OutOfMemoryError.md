#flashcards
Data: 2023-02-04 22:47
Title: [[OutOfMemoryError]]
Alias:
Header:

Когда выбрасывается ошибка [[OutOfMemoryError]]?::[[OutOfMemoryError]] выбрасывается, когда виртуальная машина Java не может создать (разместить) объект из-за нехватки памяти, а сборщик мусора не может высвободить достаточное её количество. 



Body:


Какие есть типы `OutOfMemoryError`?
!---
Ответ:
	- Область памяти, занимаемая java процессом, состоит из нескольких частей. Тип `OutOfMemoryError` зависит от того, в какой из них не хватило места.
	- `java.lang.OutOfMemoryError: Java heap space`: Не хватает места в куче, а именно, в области памяти в которую помещаются объекты, создаваемые в приложении программно. Обычно проблема кроется в утечке памяти. Размер задается параметрами `-Xms` и `-Xmx`.
	- `java.lang.OutOfMemoryError: PermGen space`: (до версии Java 8) Данная ошибка возникает при нехватке места в _Permanent_ области, размер которой задается параметрами `-XX:PermSize` и `-XX:MaxPermSize`.
	- `java.lang.OutOfMemoryError: GC overhead limit exceeded`: Данная ошибка может возникнуть как при переполнении первой, так и второй областей. Связана она с тем, что памяти осталось мало и сборщик мусора постоянно работает, пытаясь высвободить немного места. Данную ошибку можно отключить с помощью параметра `-XX:-UseGCOverheadLimit`.
	- `java.lang.OutOfMemoryError: unable to create new native thread`: Выбрасывается, когда нет возможности создавать новые потоки.
	




Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()