# Лекция первая
Все слайды [тут](http://melevir.com/static/styleru_py/slides/1.html).

### О курсе
[Слайд 3](http://melevir.com/static/styleru_py/slides/1.html?full#3):

- JS не торт, но сайты делать без него сложно. 
- Софтскилловые темы — темы, без которых все думают, что обойдутся, но нет.

[Слайд 4](http://melevir.com/static/styleru_py/slides/1.html?full#4): 

- Универсальный — на Питоне пишут и сайты, и ботов, и (чуть-чуть) мобильные приложения.
- Огромное сообщество — в данном случае не баззворд, а реальная фича: куча митапов (в том числе в Москве), отличная документация, много вопросов на StackOverflow.

[Слайд 5](http://melevir.com/static/styleru_py/slides/1.html?full#5): 

- Использовать будем Python 3. Сейчас даже крупные компании запускают новые проекты на нем. 
- Освоившись с ним, легко выучить и Python 2. В компаниях, где много legacy-кода, Python 2 еще встречается. 
- Чтобы перевести код с двушки на трешку, используют [2to3](https://docs.python.org/3.0/library/2to3.html), а затем фиксят ошибки вручную.

[Слайды 6-7](http://melevir.com/static/styleru_py/slides/1.html?full#6):
- У Питона много реализаций, но, когда говорят "Python", обычно понимают CPython. 
- Другие реализации в курсе мы трогать не будем.

### Об инструметах

[Слайд 9](http://melevir.com/static/styleru_py/slides/1.html?full#9):
- Это линуксовые команды. Чтобы попробовать, можно любой дистрибутив установить вместе в Windows или на виртуалку.
- Без этих команд невозможно жить (список неполон).

[Слайд 10](http://melevir.com/static/styleru_py/slides/1.html?full#10):
- Гит — система контроля версий.
- Сдавать первую домашку нужно будет уже с помощью него.

### О Питоне

[Слайды 12-13](http://melevir.com/static/styleru_py/slides/1.html?full#12):
- Итерировать по индексам не надо, можно ведь по элементам.

[Слайды 14-15](http://melevir.com/static/styleru_py/slides/1.html?full#14):
- Нужны и элементы, и индексы? Используйте [enumerate()](https://docs.python.org/3/library/functions.html#enumerate).

[Слайды 18-19](http://melevir.com/static/styleru_py/slides/1.html?full#18):
- Начальный и конечный индекс нужны так часто, что их можно не писать.

[Слайды 24-25](http://melevir.com/static/styleru_py/slides/1.html?full#24):
- Так можно пройти по всем элементам с четными индексами.

[Слайд 28](http://melevir.com/static/styleru_py/slides/1.html?full#28):
- Срезы работают на любых последовательностях.
