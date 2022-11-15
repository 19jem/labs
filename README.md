# lab3
1.	Використання готових Docker Images
Створюю файл compose.yml в якому записую всі залежності за інстукцією для wordpress з Docker Hub

![screen](SCREENS3/screen1.png)

І переношу це в compose.yml

![screen](SCREENS3/screen2.png)

Далі запускаю команду docker-compose up -d з папки з файлом

![screen](SCREENS3/screen3.png)

![screen](SCREENS3/screen4.png)
 
І створюю сторінку за безкоштовним шаблоном

![screen](SCREENS3/screen5.png)

2.	Використання Docker Compose
Docker Compose — інструментальний засіб, що входить до складу Docker. Воно призначене для вирішення завдань, пов'язаних із розгортанням проектів. Під час роботи в Compose ви використовуєте файл YAML для налаштування служб програми. Потім ви створюєте та запускаєте всі служби з конфігурації шляхом виконання однієї команди.
3.	Створення HTML сторінки та занесення її в Docker Image
Створити HTML сторінку із ПІБ, групою та номером лаб. роботи:

![screen](SCREENS3/screen6.png)

Створити Docker Image із цією сторінкою.
Реалізувати можливість запуску цієї сторінки з контейнера:

![screen](SCREENS3/screen7.png)

Створюю Docker image :

![screen](SCREENS3/screen8.png)

Перевірити на працездатність контейнера на основі вашого образу:

![screen](SCREENS3/screen9.png)

![screen](SCREENS3/screen10.png)

Залити готовий образ на Docker Hub:
https://hub.docker.com/u/19jem

![screen](SCREENS3/screen11.png)

4.	Скачати Docker Image когось із групи і розвернути в себе контейнер з HTML сторінкою на порті 8086 ззовні
"Пуллю" docker image Артема Магея і запускаю на порті 8086

![screen](SCREENS3/screen12.png)

![screen](SCREENS3/screen13.png)
