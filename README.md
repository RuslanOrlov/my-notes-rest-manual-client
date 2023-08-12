# my-notes-rest-manual-client
EN: A project in Java and Spring Boot for taking notes using a manually developed REST API (CLIENT SIDE ONLY).

The project implements a user interface layer, an MVC controller for processing user interface requests, as well as a REST client that interacts with the server using RestTemplate.

After launching the application in the IDE, access to it is opened by the link http://localhost:8082/

Through the user interface, you can perform:
1) operations of adding, viewing, changing, logical deletion (by the link "Status" in the list of notes) and physical deletion of a note;
2) line-by-line viewing of records and filtering of data in the list of notes;
3) uploading a list of notes in the form of a report to an external PDF file (data is uploaded to the report only about the notes available in accordance with the filtering and pagination criteria).

P.S.: This version of the application implements only the client and does not have physical access to the database.

/----------------------------------------------------------------------------------------------/

RU: Проект на языке Java и Spring Boot по учету заметок с использованием вручную разработанного REST API (ТОЛЬКО КЛИЕНТСКАЯ ЧАСТЬ).

Проект реализует слой пользовательского интерфейса, MVC контроллер для обработки запросов пользовательского интерфейса, а также REST клиент, взаимодействующий с сервером с помощью RestTemplate. 

После запуска приложения в IDE доступ к нему открывается по ссылке http://localhost:8082/

Через пользовательский интерфейс можно выполнить:
1) операции добавления, просмотра, изменения, логического удаления (по ссылке "Статус" в списке заметок) и физического удаления заметки;
2) пострачный просмотр записей и фильтрацию данных в списке заметок;
3) выгрузку списка заметок в виде отчета во веншний файл формата PDF (в отчет выгружаются данные только о  доступных в соответствии с критериями фильтрации и постраничного просмотра заметках).

P.S.: Данная версия приложения реализует только клиент и не имеет физического доступа к БД.
