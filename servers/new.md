# Установка сайта на новый VPS/VDS сервер Ubuntu/Debian (Проверено на Ubuntu 16.10)

## Взаимодействие с клиентом: Регистрация на SimpleCloud (оптимальна в большинстве случаев) и запуск облака Ubuntu 16.10:

1.Клиент регистрируется по ссылке: http://www.simplecloud.ru/start/clouddat/

2.Выбор тарифа:

2.1.: 150р./месяц - для подходит для большинства новых сайтов (кроме интернет-магазинов)

2.2.: 250р./месяц - для разработки интернет-магазинов без высокой нагрузки

2.3.: 500р./месяц - для перевоза наполненных интернет-магазинов, небольших порталов, ..., для всех, кому 20 GB не достаточно, или возможны высокие нагрузки

2.4.: 1000р./месяц - для интернет-магазинов OpenCart с 10.000 позиций, более дорогой хостинг выбирается индивидуально

3.Указать Ubuntu 16.10

4.Получить на e-mail IP и пароль от root

5.Переслать на vvmspace@gmail.com IP и пароль от root

## Запуск веб-сервера на Ubuntu 16.10 с базовыми настройками (от 1000р.):

1.Установка lamp-server:

1.1.Установка tasksel

1.2.sudo tasksel install lamp-server

1.3.Установка lamp-server из интерфейса

1.4.Запомнить и записать пароль от MySQL root

2.Установка PHPMyAdmin:

2.1.sudo apt-get install phpmyadmin

2.2.Скопировать /etc/phpmyadmin/apache.conf в /etc/apache2/conf-available/phpmyadmin.conf

2.3.Включить конфигурацию PHPMyAdmin: sudo a2enconf phpmyadmin

3.Продолжение следует
