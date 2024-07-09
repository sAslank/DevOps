# **Домашнее задание к занятию «Что такое DevOps. СI/СD» SYS-32 - Кумышев Аслан**

Задание 1
Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
1. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/1.jpg)
2. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/2.jpg)
3. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/3.jpg)
4. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/4.jpg)

Задание 2
Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
1. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20035031.jpg)
2. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20035042.jpg)
3. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20035055.jpg)
4. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20035108.jpg)
5. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20035150.jpg)
Задание 3
Что нужно сделать:

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.
1. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20054720.jpg)
2. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20054753.jpg)
3. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20065752.jpg)
4. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20065818.jpg)
5. ![alt text](https://github.com/sAslank/DevOps/blob/main/img/Скриншот%2009-07-2024%20072512.jpg)
