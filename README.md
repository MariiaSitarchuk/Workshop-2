# Workshop-2
This project is a version for tracker of things you have to do.
Here is the text in Ukrainian :-)

Завдання Goal tracker

Короткий опис завдання:
Ваше завдання - реалізувати трекер одного конкретного плану - наприклад, ви поставили собі за мету пити воду 8 разів на день - кожен раз коли ви це робите - ви заходите в програму - обираєте що от ви це зараз зробили - і вона зараховує вам +1 з 8. Як тільки є 8 разів - дата цього дня додається в колонку “успішних” днів в csv-файл, якщо за день 8 разів не набирається і наступного разу ви заходите в програму вже наступного дня - день додається в колонку “неуспішних”. 


Що необхідно реалізувати?

Взаємодію з користувачем з командною стрічки - робота команди триває доти - доки користувач не захоче закінчити роботу (опція “Вийти” має бути присутня обов’язково)
1.2 Це може мати наступний вигляд: 
	При кожному запуску програми користувач має список що сьогодні має бути досягнуто і скільки разів він що виконав сьогодні вже - це має бути реалізовано через читання з файлу. Користувач обирає що він зараз виконав - додається +1 до counter-y окремого завдання. І так для кожного завдання. Користувач має мати опцію “Вийти”, щоб закінчити виконання програми. 

Записування нової мети на день - к-сть виконання саме цієї мети на день 

2.1 Таких цілей на один може бути кілька, всі вони трекаються без пріоритетності - користувач має обирати що саме він зробив - яку саме з цілей. 

Оскільки є робота з csv файлом - то приблизний вигляд може бути таким:

Дані в таблиці мають бути посортовані по датах - не може 15 грудня іти до 14 грудня (це легко зробити - додаючи їх в таблицю лише в поточний день виконання)

Вимоги виконання:

Робота має бути розподілення на трьох людей - кожен працює із своєю частиною і заливає на гітхаб на свою гілку ! 
Програма має працювати поки користувач не обере опцію “Вийти” ( при кожному разі, коли користувач заходить, щоб просто поставити “галочку” що він ще раз виконав якесь завдання на сьогодні) 
Програма повинна зберігати наявні завдання у файл. Під час запуску програма повинна зчитати минулі завдання з файлу (якщо вони є), а під час вимкнення програма повинна зберегти поточні завдання у файл.

[![Pylint](https://github.com/anstadnik/git_workshop/actions/workflows/pylint.yml/badge.svg)](https://github.com/anstadnik/git_workshop/actions/workflows/pylint.yml)
[![Pylint](https://github.com/anstadnik/git_workshop/actions/workflows/tests.yml/badge.svg)](https://github.com/anstadnik/git_workshop/actions/workflows/tests.yml)

