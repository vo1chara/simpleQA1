<pre>
# simpleQA
Сначала заходишь в папку с XAMPP, где проекты /XAMPP/htdocs/
Там, правой кнопкой мыши внутри папки и выбрать Git Bash Here
после вести в открывшуюся консоль git clone https://github.com/destroyandromeda/simpleQA.git


После того, как стартанете в XAMPP apache и mysql
База данных находится в папке дб, ее нужно импортировать в ваш mysql с тем же названием(qa)
1) Нажимаем на контроль панели в XAMPP где mysql admin 
<p><img src="https://sun9-69.userapi.com/c851328/v851328105/1ec1f7/8p9NSRHQsTA.jpg" alt=""></p>
там Нажимаем "Создать БД" 
-> далее переходим на открывшейся панели в кладку Импорт 
-> нажимаем кнопку "Выберите файл" и выбираем файл из папки с проектом
 который находится в XAMPP\htdocs\simpleQA\DB и нажимем "Вперед"
(файл qa.sql)
<p><img src="https://sun9-65.userapi.com/c855620/v855620105/12795e/V8VuhCXDU8c.jpg" alt=""></p>
Важно, папка с содержимым проекта должна называться simpleQA и находиться в папке htdocs(для пользователей XAMPP)
/XAMPP/htdocs/SimpleQa/
----------------------/classes/
----------------------/controllers/
----------------------/core/
----------------------/DB/
----------------------/models/
----------------------/views/
----------------------/classes/
----------------------.htaccess
----------------------config.php
----------------------index.php
----------------------README.md

Это примерная структура проекта(для пользователе XAMPP)

переходите в браузере по адрессу http://localhost/simpleQA/
Это ваш проект



админ пользователь
login 123
password 123

может видеть все тесты пользователей
может добавлять/изменять/удалять тесты (они в формате вопрос-ответ)


</pre>
