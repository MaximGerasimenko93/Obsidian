#flashcards 
Data: 2022-05-02 14:41
Title: [[SOLID]]
Tags: #SOLID #АрхитектураКлассов #Архитектура #АрхитектурныеПринципы  #Принципы  # # # # # # #
Alias:
	-
Header:
	- [[SOLID]] (сокр. от [англ.](https://ru.wikipedia.org/wiki/%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9_%D1%8F%D0%B7%D1%8B%D0%BA "Английский язык") single responsibility, open–closed, Liskov substitution, interface segregation и dependency inversion)

Body:


Какие существуют [[SOLID]] принципы?
!---
Ответ:
	- [[Single responsibility]] 
	- [[Open-closed principle]]
	- [[Liskov substitution principle]]
	- [[Interface segregation principle]]
	- [[Dependency Inversion Principle]]
<!--SR:!2023-03-14,3,190-->


К каким проблемам может привести не соблюдение [[SOLID]]?
!---
Ответ:
	- Падение производительности труда по мере роста объема кода. Евгений Тюменцев
<!--SR:!2023-03-14,3,210-->

Зачем нужено использовать [[SOLID]]?
!---
Ответ:
	- Для сохранения постоянной скорости разработки по мере роста объема кода.
	- Нам нужно не модифицировать абстракции для того чтобы скорость разработки была постоянной. Но Мы их можем расширять
	- Причина почему скорость разработки падает, потому что мы меняем абстракции. 
<!--SR:!2023-03-14,3,266-->


Почему приходится править абстракции?
!---
Ответ:
	- Мы строим множество сущностей, которое не обобщает до 1 абстракции
<!--SR:!2023-03-12,1,146-->


Главы:
- [[Single responsibility]]
- [[Open-closed principle]]
- [[Liskov substitution principle]]
- [[Interface segregation principle]]
- [[Dependency Inversion Principle]]



Sources:
1) [# Принципы SOLID, о которых должен знать каждый разработчик](https://habr.com/ru/company/ruvds/blog/426413/)
2) [# SOLID (объектно-ориентированное программирование)](https://ru.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5))
3) [# Простое объяснение принципов SOLID](https://habr.com/ru/company/vk/blog/412699/)
4) [# Математическое обоснование S.O.L.I.D принципов Евгений Тюменцев](https://www.youtube.com/watch?v=CmCEdVrZQAE)
5) [О формализации процесса разработки программного обеспечения](https://cyberleninka.ru/article/n/o-formalizatsii-protsessa-razrabotki-programmnogo-obespecheniya/viewer)
6) [Формализации процесса разработки](http://msm.omsu.ru/jrns/jrn43/FormalSDP.pdf)
7) [О формальном определении абстракции](http://msm.omsu.ru/jrns/jrn45/abstraction.pdf)
8) [# Принципы S.O.L.I.D. в картинках](https://bimlibik.github.io/posts/solid-in-pictures/)
9) [The Principles of OOD](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)
10) [Тройки Хоара](https://habr.com/ru/post/268013/)
11) [Логика Хоара - Hoare logicВикипедия  site:wiki5.ru](https://wiki5.ru/wiki/Hoare_logic)
12) [# S.O.L.I.D, GRASP and Other Basic Principles of Object Oriented Design](https://www.codeproject.com/Articles/1166136/S-O-L-I-D-GRASP-and-Other-Basic-Principles-of-Obje)
13) [Причуды абстракций](https://habr.com/ru/company/tiktokcoach/blog/206994/)
14) [# SOLID](https://github.com/qcha/JBook/blob/master/oop/SOLID.md#solid)
15) [# Понятнее о S.O.L.I.D](https://habr.com/ru/post/508086/)
