Введение:

Вы можете выполнять задания в любом порядке. Но, прежде чем приступить, подумайте как модули будут взаимодействовать между собой.
[Кроме того, мы настоятельно рекомендуем сдавать это задание по частям, итеративно наращивая функциональность. Пожалуйста убедитесь что вы сдаёте на проверку более или менее завершённые модули, которые возможно запустить и протестировать]

Бизнес область: 
1)	Музыкальный магазин(песни, альбомы, пользователи и т.д.) 
2)	Сервис заказа билетов на самолет(билет, рейс, пассажир) 
3)	Свой вариант предметной области.

JPA: 
Необходимо реализовать класс DAO, который будет обеспечивать работу c БД. DAO должен работать через Entity объекты предметной области. DAO использует JPQL. 
Entity должны описывать варианты взаимодействия: One-To-One, One-To-Many. Реализовать CRUD операции. На каждую сущность своя таблица. Например, вы выбрали "Музыкальный магазин", значит нужно создать три таблицы "песни", "альбомы" и "пользователи" .
•	DAO использует NamedQuery, NativeQuery. (По желанию)
•	Entity должны описывать варианты взаимодействия: Many-To-Many. (По желанию)

Markup languages: 
Прочитать файл в формате JSON или CSV(например список песен с описанием...), распарсить и загрузить данные в БД. Выполнить обратную операцию, т.е. обратиться к таблице БД, выгрузить данные(например список песен), отформатировать в JSON и передать на view.

FE for BE developers: 
Шаблон будет предоставлен (таблица с парой CRUD операций), нужно будет сделать по аналогии для своих сущностей. Необходимо сделать таблицу сущностями из предыдущих задач , CRUD операции для них. Спиннер. Обрабатывать ошибки в модальном окне.

Inter-application communication: 
Реализовать REST API для взаимодействия с фронтом

Spring Core & MVC: 
Реализовать контроллеры для CRUD операций, сервисы для каждой сущности, сделать через JAVA конфиг(spring boot переделать на annotation-конфиг), написать Unit тесты.

Spring Boot: 
Переделать сервис на Spring Boot и успешно прогнать Unit тесты.
