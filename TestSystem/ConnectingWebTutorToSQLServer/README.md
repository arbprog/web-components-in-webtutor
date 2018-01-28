# Подключение WebTutor к SQL Server

1. В WebTutor Server заходим во вкладку `База данных`![](/TestSystem/ConnectingWebTutorToSQLServer/1.jpg)
2. Переключаем хранение данных на `MS SQL` и жмем на `Мастер настройки базы данных...`![](/TestSystem/ConnectingWebTutorToSQLServer/2.jpg)
3. Заполняем поля, жмем `Далее`  
   **Сервер БД** = Имя SQL сервера \(можете посмотреть имя в SSMS\)  
   **Название БД** = wt  
   **Поставить галку:** Создание базы данных в случае отсутствия таковой  
   **Поставить галку:** Интегрированная авторизация![](/TestSystem/ConnectingWebTutorToSQLServer/3.jpg)

4. Жмем `Далее`![](/TestSystem/ConnectingWebTutorToSQLServer/4.jpg)

5. Жмем `Завершить`![](/TestSystem/ConnectingWebTutorToSQLServer/5.jpg)

6. Если вам необходим полнотекстовый поиск, используйте [инструкцию](http://news.websoft.ru/view_doc.html?mode=doc&doc_id=5900009198344233435) для создания SQL Job.



