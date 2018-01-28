# Запуск WebTutor

1. Заходим в IIS и запускаем: 

**Сервер**  
    ![](/TestSystem/StartWebTutor/1.jpg)  
   **Пул WebTutorCorpServer**  
   ![](/TestSystem/StartWebTutor/2.jpg)

**Сайт WebTutorCorpServer**  
   ![](/TestSystem/StartWebTutor/3.jpg)

1. Открываем в браузере страницу [https://localhost:8787](https://www.gitbook.com/book/maksimyurkov/progressive-webtutor/edit#), она будет в статусе загрузки.  
   Загружаться она будет до тех пор, пока в SQL базе данных `wt` не создадутся все необходимые таблицы WebTutor, это займет ~ 10 минут. \(можете посмотреть как таблицы появляются в SSMS\)  
   ![](/TestSystem/StartWebTutor/4.jpg)

2. Когда создание таблиц в SQL завершится, по адресу [https://localhost:8787](https://localhost:8787) будет такая картина  
   ![](/TestSystem/StartWebTutor/5.jpg)

3. Запускаем WebTutor Administrator

4. Пишем `localhost:8787`  
   ![](/TestSystem/StartWebTutor/6.jpg)

5. Нажимаем на `Русский`  
   ![](/TestSystem/StartWebTutor/7.jpg)

6. Вводим логин: `user1`, пароль: `user1`, жмем `ОК`  
   ![](/TestSystem/StartWebTutor/8.jpg)

7. Переходим в  `Портал` - `Узлы` - `Хост по умолчанию`  
   ![](/TestSystem/StartWebTutor/9.jpg)

8. Меняем порт на `8787`  
   ![](/TestSystem/StartWebTutor/10.jpg)

9. После этого портал начнет корректно открываться по адресу [https://localhost:8787](https://localhost:8787)  
   ![](/TestSystem/StartWebTutor/11.jpg)



