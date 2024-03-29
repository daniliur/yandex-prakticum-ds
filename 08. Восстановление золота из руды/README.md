# Восстановление золота из руды

*Задача: подготовить прототип модели машинного обучения для предсказания коэффициента восстановления золота из золотосодержащей руды.*

Необходимо предсказать коэффициент восстановления как после этапа флотации, так и на финальном этапе. Для оценки работы модели применяется метрика *sMAPE*.

## Проведены исследование и предобработка данных.

## Была проведена подготовка функций для моделирования
- ф-я расчета sMAPE;
- ф-я для проведения кросс-валидации;
- ф-я для проведения моделирования и расчета sMAPE сразу для всех этапов.

## Проведено моделирование с помощью следующих алгоритмов:
- линейная регрессия;
- решающее дерево;
- случайный лес.

Результаты моделей были сравнены с DummyRegressor.

Наилучшей моделью оказался случайный лес с 30 деревьями и глубиной 6. Финальная sMAPE для данной модели на тестовой выборке составила 7.34.

## Библиотеки и методы
* `pandas`
* `matplotlib`
* `seaborn`
* `sklearn`
* `cross-validation`
* `sMAPE`
* `numpy`