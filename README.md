# my-notes-rest-manual-client
EN: A project in Java and Spring Boot for taking notes using a manually developed REST API (CLIENT SIDE ONLY).

The project implements a user interface layer, an MVC controller for processing user interface requests, as well as a REST client that interacts with the server using RestTemplate.

The application runs in the IDE and is available via the link http://localhost:8082/

1. Data about notes in the client application is presented in the form of DTO objects and lists of DTO objects.
2. Through the user interface of the application, you can perform:
- operations of adding, viewing, changing, logical deletion (by the "Status" link in the list of notes) and physical deletion of a note;
- page-by-page view of the list of notes and filtering of data in the list of notes;
- uploading a list of notes in the form of a PDF report (data is uploaded only on available notes in accordance with the criteria for filtering and pagination).
3. The client validates the data entered/modified by the user in html forms. Validation is implemented using annotations in the DTO class, as well as at the level of the MVC controller and html forms.

P.S.: This version of the application implements only the client and does not have physical access to the database.

/----------------------------------------------------------------------------------------------/

RU: Проект на языке Java и Spring Boot по учету заметок с использованием вручную разработанного REST API (ТОЛЬКО КЛИЕНТСКАЯ ЧАСТЬ).

Проект реализует слой пользовательского интерфейса, MVC контроллер для обработки запросов пользовательского интерфейса, а также REST клиент, взаимодействующий с сервером с помощью RestTemplate. 

Приложение запускается в IDE и доступно по ссылке http://localhost:8082/

1. Данные о заметках в клиентском приложении представлены в виде DTO объектов и списков DTO объектов.
2. Через пользовательский интерфейс приложения можно выполнить:
- операции добавления, просмотра, изменения, логического удаления (по ссылке "Статус" в списке заметок) и физического удаления заметки;
- пострачный просмотр списка заметок и фильтрацию данных в списке заметок;
- выгрузку списка заметок в виде отчета в формате PDF (выгружаются данные только о доступных заметках в соответствии с критериями фильтрации и постраничного просмотра).
3. Клиент выполняет валидацию данных, вводимых/изменяемых пользователем в html формах. Валидация реализуется с помощью аннотаций в классе DTO, а также на уровне MVC контроллера и html форм.

P.S.: Данная версия приложения реализует только клиент и не имеет физического доступа к БД.
