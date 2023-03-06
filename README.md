# Промежуточная аттестация
- ## Java
- ## Linux

 
- # Задание 1 Linux
 
>1. Используйте команды операционной системы Linux 
и создайте две новых директории – «Игрушки для школьников» и «Игрушки для дошколят»
>2. Создайте в директории «Игрушки для школьников» текстовые файлы - «Роботы», «Конструктор», «Настольные игры»
>3. Создайте в директории «Игрушки для дошколят» текстовые файлы «Мягкие игрушки», «Куклы», «Машинки»
>4. Объединить 2 директории в одну «Имя Игрушки»
>5. Переименовать директорию «Имя Игрушки» в «Игрушки»
>6. Просмотреть содержимое каталога «Игрушки».
>7. Установить и удалить snap-пакет. (Любой, какой хотите)
>8. Добавить произвольную задачу для выполнения каждые 3 минуты 
(Например, запись в текстовый файл чего-то или копирование из каталога А в каталог Б).
 
 
- # Задание 2 Java
 
Необходимо написать программу – розыгрыша игрушек в магазине детских товаров.
Стараемся применять ООП и работу с файлами.
 
Желательный функционал программы:

В программе должен быть минимум один класс со следующими полями:
>- id игрушки,
>- текстовое название,
>- количество
>- частота выпадения игрушки (вес в % от 100)

методы: 
>- Метод добавление новых игрушек и возможность изменения веса (частоты выпадения игрушки)
>- Возможность организовать розыгрыш игрушек.
Например, следующим образом:
С помощью метода выбора призовой игрушки – мы получаем эту призовую игрушку и записываем в список\массив.
Это список призовых игрушек, которые ожидают выдачи.
>- Еще у нас должен быть метод – получения призовой игрушки.
После его вызова – мы удаляем из списка\массива первую игрушку и сдвигаем массив. 
А эту игрушку записываем в текстовый файл.
Не забываем уменьшить количество игрушек