# Игра «Жизнь»

Реализация [известного клеточного автомата](https://ru.wikipedia.org/wiki/%D0%98%D0%B3%D1%80%D0%B0_%C2%AB%D0%96%D0%B8%D0%B7%D0%BD%D1%8C%C2%BB), придуманного английским математиком Джоном Конвеем в 1970 году.

**Проект реализован с использованием**: WSL & VS Code.

**Участники проекта:**

- Коновалов Владимир,  73200073;
- Кулеш Иван, Шифр: *******.

**Группа:** ЗП-021.
##

Приложение моделирует игру «Жизнь» - плоское клеточное поле, состоящее из пустых клеток и организмов. 
Развитие любой конфигурации определяют 2 закона:
- организм выживает, если имеет 2 или 3 соседей и умирает в противоположном случае;
- новый организм рождается, если число соседей равно 3.

После запуска приложения обрабатывается файл, содержащий в себе количество клеток по высоте и ширине, 
а также символы, которыми будет представлена живая и не живая клетка.(Дописать). <br>
По нажатию любой кнопки отображается следующее поколение, в соответствии с правилами игры.

## Загрузка проекта на локальный репозиторий (ИЛИ УСТАНОВКА?)

```
git clone https://github.com/bdfyvaldis/GameOfLife.git
cd GameOfLife
```

## Запуск 

```
make
make run
```

## Тестирование

```
make runtests
```
