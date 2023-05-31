# Основная задача проекта
Построить модель, которая смогла бы предсказывать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. 

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
## Описание проекта
Проект предоставлен промышленной компанией, которая разрабатывает решения для других промышленных предприятий, и заинтересованной в оптимизации и повышении эффективности добычи золота. 

Нам предоставлены данные, которые содержат информацию о концентрации различных металлов на разных этапах производства. Так же каждый этап содержит несколько параметров: объём воздуха, уровень жидкости, размер гранул сырья и скорость подачи.

Для решения задачи мы введём новую метрику качества — sMAPE (Symmetric Mean Absolute Percentage Error или «симметричное среднее абсолютное процентное отклонение»), которая выражается не в абсолютных величинах, а в относительных. Эта метрика одинаково учитывает масштаб и целевого признака, и предсказания.

## План проекта

- 1. Подготовка данных
    - 1.1 Открытие и изучение
    - 1.2 Проверка эффективности обогащения
    - 1.3 Пропущенные столбцы в тестовой выборке
    - 1.4 Пропуски в датафрейме
- 2. Анализ данных
    - 2.1 Концентрация металлов (Au, Ag, Pb) на различных этапах очистки
    - 2.2 Размер гранул сырья на обучающей и тестовой выборках
    - 2.3 Суммарные концентрации всех веществ на разных стадиях
- 3. Построение моделей
    - 3.1 Функция для вычисления sMAPE
    - 3.2 Обучение моделей
    - 3.3 Итоговое sMAPE)
