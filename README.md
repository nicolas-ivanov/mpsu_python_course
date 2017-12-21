
# Краткое руководство с примерами по Python 2

## Содержание курса
1. [Простейшие типы данных и арифметические операции](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/1.%20%D0%9F%D1%80%D0%BE%D1%81%D1%82%D0%B5%D0%B9%D1%88%D0%B8%D0%B5%20%D1%82%D0%B8%D0%BF%D1%8B%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D0%B0%D1%80%D0%B8%D1%84%D0%BC%D0%B5%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8.ipynb)
1. [Списки](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/2.%20%D0%A1%D0%BF%D0%B8%D1%81%D0%BA%D0%B8.ipynb)
1. [Управляющие конструкции](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/3.%20%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D1%8F%D1%8E%D1%89%D0%B8%D0%B5%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8.ipynb)
1. [Строки](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/4.%20%D0%A1%D1%82%D1%80%D0%BE%D0%BA%D0%B8.ipynb)
1. [Кортежи, множества, словари](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/5.%20%D0%9A%D0%BE%D1%80%D1%82%D0%B5%D0%B6%D0%B8%2C%20%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B0%2C%20%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%B8.ipynb)
1. [Ввод и вывод. Функции и память](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/6.%20%D0%92%D0%B2%D0%BE%D0%B4%20%D0%B8%20%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4.%20%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8%20%D0%B8%20%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C.ipynb)
1. [Классы](https://github.com/nicolas-ivanov/mpsu_python_course/blob/master/7.%20%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D1%8B.ipynb)


## Введение
На данный момент Python является, пожалуй, самым популярным высокоуровневым языком программирования, используемым для учебных и научных целей. Синтаксис ядра Python минималистичен, но в то же время стандартная библиотека включает большой объём полезных функций. 

Кроме того, существует множество популярных библиотек для удобной работы с данными (такие как `numpy` и `pandas`) и реализованными алгоритмами (например, `scipy`), которые делают язык Python очень удобным инструментом в руках как начинающих исследователей, так и профессиональных разработчиков.

В этом курсе для изучения возможностей Python мы будем использовать Jupyter Notebook - интерактивную оболочку языка Python. Ноутбуки это ваши рабочие "рабочие тетрадки" - их можно читать, в них можно писать код и комментарии к нему, а потом написанный код запускать.

Чтобы читать ноутбуки не требуется ничего, кроме браузера. Оглавление к курсу располагается ниже - открываем нужную главу и читаем. 

Однако британские ученые заметили, что единственный способ научиться писать код - это писать код самому. Поэтому устанавливайте Jupyter Notebook на ваш компьютер, как описано ниже, и вперед кодить.

## Установка Jupyter Notebook и начало работы
Чтобы установить Python, Jupyter Notebook, а также все необходимые зависимости, проще всего воспользоваться дистрибутивом Anaconda: https://www.continuum.io/downloads

Загружайте версию с Python 2.7 для вашей операционной системы и далее следуйте инструкции по установке: https://docs.anaconda.com/anaconda/install/

После того, как этап с Anaconda пройден, переходим в любимую директорию и загружаем туда репозиторий с нашими ноутбуками:
```bash
  cd ~/my_favourite_folder/
  git clone git@github.com:nicolas-ivanov/mpsu_python_course.git
```
Переходим в появившуюся директорию и запускаем Jupyter Notebook следующей командой:
```bash
  cd mpsu_python_course
  jupyter-notebook
```
В браузере откроется новое окошко, в котором нужно выбрать нужный вам ноутбук.
Содержимое ячеек ноутбука можно и нужно менять: для ячеек с обычным текстом режим редактирования активируется двойным щелчком мыши, а для выполнения ячеек используйте комбинацию клавиш `Ctrl-Enter`.

Полное описание возможностей Jupyter Notebook выходит за рамки данного курса, поэтому сошлёмся на оффициальную документацию на английском: http://nbviewer.jupyter.org/github/ipython/ipython/blob/3.x/examples/Notebook/Index.ipynb

## Ещё полезные ссылки
* Официальная документация Python 2: http://docs.python.org/2/.
* Официальное руководство с примерами: http://docs.python.org/2/tutorial/index.html
* Различия между Python2 и Python3 https://wiki.python.org/moin/Python2orPython3
