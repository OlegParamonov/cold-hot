# Описание проекта
* Написать программу для игры "Холодно-горячо"(cold-hot). Игрок пытается угадать случайное трехзначное число (без повторяющихся цифр), сгенерированное компьютером. После каждой попытки компьютер предоставляет игроку подсказки трех типов:
	* "Холодно". Ни одна цифра не отгадана.
	* "Тепло" Одна цифра отгадана, но не отгадана ее позиция.
	* "Горячо". Одна цифра и ее позиция отгадана. Компьютер может дать несколько подсказок, сортируемых в алфавитном порядке. Если секретное число 456, а предположение игрока — 546, подсказки будут иметь вид «Горячо Тепло Тепло». Подсказка «Горячо» относится к 6, а «Тепло Тепло» — к 4 и 5.

* * *

* В программе реализованы три режима, которым соответствуют ключи:
    * `--new`. Новая игра.
    * `--list`. Вывод списка всех сохраненных игр.
    * `--replay id`. Повтор игры с идентификатором id.

* * *

## Требования

Минимальная версия PHP: 7.4.7 
Минимальная версия Composer: 1.9.3

* * *

## Инструкция по установке и запуску игры

Из Github:

1. Склонировать проект на локальную машину;
2. Установить composer, если он не установлен;
3. Перейти в корневой каталог;
4. Выполнить в консоли команду `composer update`;
5. Перейти в каталог bin из корнегого каталога и запустить файл cold-hot.bat.

Из Packagist:

1. Установить composer, если он не установлен;
2. Перейти в каталог, в который вы будете клонировать проект;
3. Выполнить команду `composer require paramonov/cold-hot`;
4. Перейти в каталог vendor/bin;
5. Запустить файл cold-hot.bat.

* * *

## Ссылки

Packagist: <https://packagist.org/packages/paramonov/cold-hot>
