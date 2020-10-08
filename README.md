# Консольная игра виселица

![Screenshot from 2020-10-08 13-48-55](https://user-images.githubusercontent.com/62602107/95455010-e3a50b00-0975-11eb-97bd-940e5889213e.png)

Игра написана на языке Ruby версии 2.7.1. Для работы игры необходимо, чтобы
был установлен гем [bundler](https://bundler.io/). 

Для запуска игры необходимо выполнить следующее:
1. Скачать архив с программой, распаковать его, зайти в папку hangman-master
2. В терминале необходимо ввести `bundle install` и дождаться окончания
установки требуемых библиотек.
3. Запустить игру, набрав `ruby main.rb`  

## Правила игры
Принцип игры описан на сайте [википедии](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)) 
1. В консоли выводится случайное слово из файла "words.txt", который находится
в папке "data".
2. Пользователю дается 7 попыток, чтобы отгадать слово.
3. Буквы "Е" и "Ё", а также "И" и "Й" попарно считаются идентичными. 

Добавлять или удалять слова для игры можно редактируя файл "words.txt", который
находится в папке "data". 

