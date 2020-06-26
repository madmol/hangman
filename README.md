# Консольная игра виселица

Игра написана на языке Ruby версии 2.7.1. Для запуска игры необходимо скачать 
архив с программой, распаковать его, зайти в папку hangman-master
и в консоли ввести 

`ruby main.rb`

## Правила игры
Принцип игры описан на сайте [википедии](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)) 
1. В консоли выводится случайное слово из файла "words.txt", который находится
в папке "data".
2. Пользователю дается 7 попыток, чтобы отгадать слово.
3. Буквы "Е" и "Ё", а также "И" и "Й" попарно считаются идентичными. 

Добавлять или удалять слова для игры можно редактируя файл "words.txt", который
находится в папке "data". 

