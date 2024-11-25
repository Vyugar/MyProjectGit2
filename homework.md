# Урок 1

# Первый файл по контролю версий

# Инструкцию по работе с Git

## Заголовки

Чтобы выделить заголовок нужно в начале строки проставить символ #. Чтобы выделить подзаголовок нужно в начале строки проставить символ ##. Пример:

# Пример заголовка

## Пример подзаголовка

## Выделение текста

Чтобы выделить текст курсивом нужно в начале и в конце текста указать символ *. Пример:

*Курсив*

Чтобы выделить текст полужирным нужно в начале и в конце текста указать символ **. Пример:

**Полужирный**

Чтобы зачеркнуть текст нужно в начале и в конце текста указать символ ~~. Например:

~~Зачеркнутый текст~~

## Списки

Чтобы создать ненумерованные списки нужно в начале строки проставить символ * и через пробел написать нужный текст. Пример:

* элемент 1
* элемент 2
* элемент 3

Чтобы создать нумерованные списки нужно в начале строки проставить цифру с точкой и через пробел написать нужный текст. Пример:

1. Первый элемент нумерованного списка
2. Второй элемент нумерованного списка

## Вставка изображений и ссылок

Чтобы вставить изображение нужно указать текст изображения, заключив его в квадратные скобки с восклицательным знаком вначале, и сразу после — URL-адрес, заключенный в круглые скобки: ![название] (http://... .ru/).
 Пример:

![картинка](https://miro.medium.com/max/1400/1*bvMUGHtl8oJP5rZPV7X8eg.png)

Чтобы вставить ссылку нужно указать текст ссылки, заключив его в квадратные скобки, и сразу после — URL-адрес, заключенный в круглые [cсылка] (http://... .ru/). Пример:

[Ссылка](https://learnxinyminutes.com/docs/ru-ru/markdown-ru/#links)

## Основные команды

* git init - добавить папку к репозиторию
* git add - добавить отслеживание файла
* git commit -m "комментарий" - добавить комментарий (зафиксировать текущее состояние)
* git diff - посмотреть разницу изменений в файле
* clear - очистить терминал
* git log - вывести список изменений в файле (журнал всех действий)
* git config --global user.name "< name >" - установить имя пользователя
* git config --global user.email "< email >" - установить почту пользователя
* git checkout - переход между версиями изменений файла
* git status - вывести статус изменений