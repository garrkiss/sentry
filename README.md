# Домашнее задание к занятию "`Платформа мониторинга Sentry`" - `Бакулев Евгений`

# Задание 1

![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/1.png)

# Задание 2

1. Перешел в список событий проекта, выбрал созданное событие и нажал на Resolve:
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/2.png)

2. Stack trace
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/2-1.png)

3. Cписок событий проекта после нажатия Resolved:
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/2-2.png)

# Задание 3

1. Выбрал проект и создал дефолтное правило алёртинга с указанием канала отправки оповещений:
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/3.png)

2. Снова сгенерировал событие Generate sample event

3. Получил на электронную почту оповещение от алёртинга:
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/3-1.png)

4. Дополнительно поэкспериментировал с правилами алёртинга. Например, настроил правило алёртинга, если задача создана или переведена из состояния "Решенные" в "Не решенные", то через 10 минут в доступные каналы связи, например, электронную почту, придет оповещение:
![Скриншот](https://github.com/garrkiss/sentry/blob/main/img/3-2.png)