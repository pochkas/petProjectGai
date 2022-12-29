Pet-project
Симулирует работу с базами данных ГАИ по штрафам.

В базе данных хранятся следующие данные: имя пользователя, имя сотрудника ГАИ, номер машины, дата выставления штрафа, стоимость штрафа, дата последнего дня оплаты штрафа и др

В данном проекте можно добавлять, обновлять, удалять данные, выводить всю информацию по одному или нескольким данным.

Для просмотра проекта необходимо запустить его и перейти по ссылке:
http://localhost:8080/swagger-ui.html

Проект на Gradle c поддержкой SpringBoot и Swagger

Чтобы запустить:
gradle clean build
Затем:
java -jar  build/libs/backend_gai-0.0.1-SNAPSHOT.jar