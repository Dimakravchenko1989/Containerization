***Home Work 1. Механизмы пространства имен***

Задание: необходимо продемонстрировать изоляцию одного и того же приложения (как решено на семинаре - командного интерпретатора) в различных пространствах имен.

Формат сдачи ДЗ: предоставить доказательства выполнения задания посредством ссылки на google-документ с правами на комментирование/редактирование.
Результатом работы будет: текст объяснения, логи выполнения, история команд и скриншоты (важно придерживаться такой последовательности).
В названии работы должны быть указаны ФИ, номер группы и номер урока.

***Home Work 2. Механизмы контрольных групп***

1. Запустить контейнер с ubuntu, используя механизм LXC
2. Ограничить контейнер 256 Мб ОЗУ и проверить, что ограничение работает

Задание по желанию ..

4. Добавить автозапуск контейнеру, перезагрузить ОС и убедиться, что контейнер действительно запустился самостоятельно
5. ''при создании указать файл, куда записывать логи
6. ''после перезагрузки проанализировать логи



***HomeWork 3. Введение в Docker***

Задание:
1. Запустить контейнер с БД, отличной от mariaDB, используя инструкции на сайте: https://hub.docker.com/

По желанию - 

3. заполнить БД данными через консоль
4. запустить phpmyadmin (в контейнере) и через веб проверить, что все введенные данные доступны


Задание

Создать папку, которую мы будем готовы смонтировать в контейнер

В этой папке создать файл test.txt и наполнить данными

В домашней директории создать файл test.txt, который также необходимо будет смонтировать в контейнер и наполнить совершенно другими данными

Создать контейнер из образа ubuntu:22.10

Задать ему имя

Задать hostname

Смонтировать созданную ранее папку с хоста в контейнер

Смонтировать созданный ранее текстовый файл внутрь смонтированной папки, чтобы он пересекался с созданным ранее файлом в этой папке. Просмотреть этот файл.

Формат сдачи ДЗ: предоставить доказательства выполнения задания посредством ссылки на google-документ с правами на комментирование/редактирование.
Результатом работы будет: текст объяснения, логи выполнения, история команд и скриншоты (важно придерживаться такой последовательности).
В названии работы должны быть указаны ФИ, номер группы и номер урока.

***HomeWork 4. Dockerfile и слои***
 
Задание: необходимо создать Dockerfile, основанный на любом образе (вы в праве выбрать самостоятельно).
В него необходимо поместить приложение, написанное на любом известном вам языке программирования (Python, Java, C, С#, C++).
При запуске контейнера должно запускаться самостоятельно написанное приложение.