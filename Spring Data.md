#flashcards #Spring 
Data: 2023-02-18 11:42
Title: [[Spring Data]]
Alias:
Header:

Что такое [[Spring Data]]?::[[Spring Data]] – это дополнительный удобный механизм для взаимодействия с сущностями базы данных, организации их в репозитории, извлечение данных, изменение, в каких то случаях для этого будет достаточно объявить интерфейс и метод в нем, без имплементации.
<!--SR:!2023-03-12,1,130-->



Body:



#Spring 
Назовите основное понятие Spring Data.
!---
Ответ:
	- Основное понятие в Spring Data — это репозиторий. Это несколько интерфейсов которые используют JPA Entity для взаимодействия с ней. 
	- Так например интерфейс `public interface CrudRepository<T, ID extends Serializable> extends Repository<T, ID>` обеспечивает основные операции по поиску, сохранения, удалению данных (CRUD операции), так же есть PagingAndSortingRepository, JpaRepository.
<!--SR:!2023-03-12,2,130-->


#Spring 
Как происходит создание нативного запроса в SpringData?
!---
Ответ:
	- Создание нативного запроса в SpringData происходит через использование аннотаций `@Modifying`, `@Transactional`, и в `@Query` пишем наш запрос.
<!--SR:!2023-03-11,1,164-->



Главы:
-


Sources:
- [ ] [Вопросы для собеседования на Java Developer](https://github.com/enhorse/java-interview/blob/master/README.md#%D0%9E%D0%9E%D0%9F)
- [ ] []()
- [ ] []()
