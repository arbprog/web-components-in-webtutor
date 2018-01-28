# FTP доступ

1. Заходим в IIS
2. Нажимаем на `Sites (Сайты)`, затем на `Add FTP Site... (Добавить FTP Сайт...)`![](/TestSystem/FTPAccess/1.jpg)
3. Заполняем поля, жмем `Next`  
   **FTP site name** = WebTutorFTP  
   **Physical part** = C:\Program Files\WebSoft\WebTutorServer\wt\web  
   ![](/TestSystem/FTPAccess/2.jpg)

4. Выбираем **SSL** = No SSL, жмем `Next`  
   ![](/TestSystem/FTPAccess/3.jpg)

5. Заполняем поля, жмем `Next`  
   **Authentication** = Basic  
   **Allow access to** = Specified roles or user groups = FTPusers  
   **Permissions** = Read, Write  
   ![](/TestSystem/FTPAccess/4.jpg)

6. В поиске Windows \(возле кнопки Пуск\) пишем Computer Management, заходим туда  
   ![](/TestSystem/FTPAccess/5.jpg)

7. Переходим в раздел `System Tools` - `Local Users and Groups`, жмем правой кнопкой мыши по `Users`, затем жмем на `New user...`![](/TestSystem/FTPAccess/6.jpg)

8. Заполняем поля, жмем `Create`, затем `Close`  
   **User Name** = Vasia  
   **Password** = на свое усмотрение  
   Выделяем:  
   User cannot change password  
   Password never expires  
   ![](/TestSystem/FTPAccess/7.jpg)

9. Переходим в раздел `System Tools` - `Local Users and Groups`, жмем правой кнопкой мыши по `Groups`, затем жмем на `New group...`![](/TestSystem/FTPAccess/8.jpg)

10. Заполняем поле  
    **Group Name** = FTPusers  
    затем жмем `Add...` и добавляем Vasia  
    после этого жмем `Create`, затем `Close`![](/TestSystem/FTPAccess/9.jpg)



