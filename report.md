# Отчёт
## Установка текстового редактора
Так как в системе нет предустановленного текстового редактора gedit, установим его с помощью команды
```
sudo apt install
```
![image](https://github.com/user-attachments/assets/6834eade-6357-4d5d-b51f-a11d3a4709a6)
## Создание и открытие файла
С помощью установленной программы создадим и откроем файл script.bash
```
gedit script.bash
```
![image](https://github.com/user-attachments/assets/77c6c48b-fd41-40c4-8293-ef11f0eb88c1)
## Скрипт
Напишем скрипт, приветствующий всякого, кто его запустит. Для этого воспользуемся командой echo, которая выводит строку текста в терминал. Строка "Welocme, $1" выводит приветственное слово welcome и указанное при запуске имя. Так как имя может состоять из произвольного количества слов, но мы передаём значение $1. Тогда в выводимую строчку вместо $1 подставляются все введённые параметры.

![image](https://github.com/user-attachments/assets/a151d735-d723-4797-8814-eceed9f44f36)
## Запуск скрипта
![image](https://github.com/user-attachments/assets/1ddda55a-d1da-4810-aafd-496a2137f52d)
