# ESCHOOL
Информационная система "Электронный дневник и журнал" 

## Установка 
1. Создать базу MySQL eschool
2. Выполнить скрипт (script.sql)
3. Добавить в таблицу role роли 

INSERT INTO `role` VALUES (1,'Классный руководитель'),(2,'Администратор'),(3,'Учитель'),(4,'Учащийся');

4. Добавить в таблицу teacher администратора (login - admin; password - 12345; hash - 827ccb0eea8a706c4c34a16891f84e7b; role_id - 2; teacher_name - Администратор; teacher status - 1)

INSERT INTO `teacher` VALUES (1,'admin','12345','827ccb0eea8a706c4c34a16891f84e7b',2,'Администратор',1);

5. Разместить проект на сервере 
6. В файле application/config/database.php прописать подключение к базе данных 
7. В файле application/config/config.php настроить $config['base_url'] 


