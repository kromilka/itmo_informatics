# Отчет по лабораторной №1
## Начало работы и Linux
Сначала на виртуальной машине с ОС linux был сгенерирован rsa ключ для дальнейшего клонирования репозитория с Лабораторной работой №1, что видно на рисунке 1.

![image](https://github.com/kromilka/itmo_informatics/assets/60718613/4afa60b4-f962-409b-9e7c-99c00ce94074)
Рисунок 1 - команды для генерации SSH ключа и вывода для дальнейшего подключения к github

В настройках для подключения SSH ключ был добавлен (рисунок 2).

![image](https://github.com/kromilka/itmo_informatics/assets/60718613/4a7104bf-951f-4783-82a5-159d44702f17)
Рисунок 2

Далее, так как на виртуалке не был установлен git или его библиотеки, была выполнена установка git (рисунок 3). После этого в корневую папку был склонирован репозиторий Лабораторной №1 (рисунок 4).
![image](https://github.com/kromilka/itmo_informatics/assets/60718613/7ef07efa-bd46-41b6-b0bc-0fe0741f1814)
Рисунок 3

![image](https://github.com/kromilka/itmo_informatics/assets/60718613/541642ed-d951-4e29-a72d-4e0a4488372b)
Рисунок 4

Был создан файл script.bash (рисунок 5) и открыт для редактирования с помощью команды gedit. Согласно README.md в файл была вписана строка пути к bash и команда echo (рисунок 6).
![image](https://github.com/kromilka/itmo_informatics/assets/60718613/21bd1d03-27da-4312-9cbb-0b9b8a1d05f3)

Рисунок 5

![image](https://github.com/kromilka/itmo_informatics/assets/60718613/a95ac1da-bc2f-4c5a-ae7b-3854f31480a1)

Рисунок 6

Файл script.bash был сохранен и запущщен из терминала (рисунок 7).
![image](https://github.com/kromilka/itmo_informatics/assets/60718613/c58d32cc-6b88-4563-a46b-515b48830b8f)

Рисунок 7


## Задача и решение
Необходимо было модифицировать файл script.bash таким образом, чтобы при его запуске в терминале в виде 
```
bash script.bash Vasya Pupkin
```
Вывод был
> Welcome, Vasya Pupkin

Решение и демонстрация изображены на рисунках 8 и 9, соответственно. Ссылка на файл-решение [script.bash](https://github.com/kromilka/itmo_informatics/blob/main/script.bash)
![image](https://github.com/kromilka/itmo_informatics/assets/60718613/d7851546-c47a-4a97-951e-c5c94ce5db2d)

Рисунок 8

![image](https://github.com/kromilka/itmo_informatics/assets/60718613/eac6dd9b-b3db-418e-9dba-83b089655484)

Рисунок 9
