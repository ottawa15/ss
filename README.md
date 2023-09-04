# Портфолио: аналитик данных

## Обо мне 
Привет! Меня зовут Сергей, я начинающий аналитик данных. Мне нравится производить расчеты, строить гипотезы, подтверждать и опровергать их, находить закономерности и уязвимости в продуктах/системах. Умение погрузиться в бизнес-процессы и досконально изучить их позволяет делать правильные выводы. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>
## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``
- Языки программирования и библиотеки: ``Python``
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
## Проекты

**<p> Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра</p>**
**<p>Что нужно было сделать:<p>**
<ol>
  <li>Необходимо посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность.</li>
  <li>Собрать калькулятор юнит-экономики и хорошую наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на нашей платформе.</li>
</ol>

<p>Как решал:
 
**Для понимания картины, с помощью сводных таблиц были рассчитаны следующие метрики:**

1. Кол-во подписок в каждый месяц       
2. Кол-во просмотров в каждый месяц  
3. Кол-во уникальных просматривающих пользователей в каждый месяц
4. Дата первого просмотра для каждого юзера
5. Кол-во первых просмотров для пользователя в каждый месяц
6. Среднее кол-во просмотров на одного юзера в каждом месяце

  **Для создания калькулятора юнит-экономики нашего продукта, были рассчитаны следующие метрики:**

1. Количество повторных оплат в каждом месяце
2. Retention для каждого месяца
3. Среднее геометрическое Retention    
4. Лайфтайм       
5. LTR 
6. CAC    
7. Маржинальность
<p>

> <a href="https://github.com/ottawa15/my_portfolio/commit/9b583160adb7fccee9f8f283322f2a5b3200edd8"> Калькулятор юнит-экономики, Визуализация, Расчет метрик</a>
    
**<p> Выводы (итоги):<p>**
<ol> Юнит-экономика продукта посчитана, калькулятор юнит-экономики собран, сценарий по настройке параметров для выхода на 25-процентную маржинальность предложен, визуализация создана.
 
</ol>

**<p> Проект 2: Моделирование изменения балансов студентов с помощью SQL</p>**
**<p>Что нужно было сделать:<p>**
<ol>
Задача — смоделировать изменение балансов (количество уроков) студентов.
  
Необходимо посчитать: 
  
- сколько всего уроков было на балансе всех учеников за каждый календарный день;
- как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков).
  
Необходимо создать таблицу, где будут балансы каждого студента за каждый день.</li>

<p> 
 Как решал:
  
**При решение использовались:**
    
 - запросы с условиями CASE WHEN и WHERE;
  
 - агрегирующие функции COUNT, SUM, AVG, MAX, MIN;
  
 - разные типы соединений для таблиц JOIN;
  
 - подзапросы и CTE (common table expression) WITH;
  
 - оконные фцнкции с операторами OVER, PARTITION BY, ORDER BY; 

<p>
  
> <a href="https://github.com/ottawa15/my_portfolio/commit/19ac0b89ec1882670471fc9c406abe64ab39260d"> Результат, визуализация, код</a>
 
**<p> Выводы (итоги):<p>**  
<ol> Изменения балансов посчитаны, таблица создана, визуализация построена, гипотезы выдвинуты.
</ol>

**<p> Проект 3: Эксперимент с A/B тестом в Phyton и калькулятор на основе полученных данных в Excel </p>**
**<p>Что нужно было сделать:<p>**
<ol>
<!-- Задача — проанализировать АБ-Тест, проведенный во всех городах, где фунционируют торговые точки. -->
  
Необходимо: 
- проанализировать и визуализировать результаты; .  
- провести сегментацию;
- сделать выводы и сформулировать рекомендации для дальнейших запусков АБ Теста;
- построить таблицу, которая будет в удобной форме хранить результаты АБ Теста;
- полученную таблицу необходимо выгрузить в Excel.
</li>

<p> 
 Как решал:
  
**При решение использовались:**
Все действия были проведены в окружение Jupyter Notebook.

 - Импорт и анализ таблиц (импортировали данные, исключили из таблиц все строки, в которых есть нулловые значения, построили гисторграммы)
  
 - Объединение таблиц (првоели агрегацию данных, объединли таблицы с помощью ф-ции merge()); 
  
 - Автоматизация статистических вычислений (создали функцию, которая будет вычислять значение t-критерия (критерия Стьюдента) и p_value для сравнения средних,
   создали ф-цию mann_whitney_func, которая будет рассчитывать значение критерия Манна Уитни и p_value для сравнения распределений);
  
 - Чистка неверно заполненных точек (запустили цикл по всем торговым точкам и добавили к созданном списку все торговые точки, в которых не было заплачено ни одного рубля);
  
 - Расчет общих результатов АБ Теста;
   
 - Сегментация результатов АБ Теста по городам и торговым точкам;

 - Отчет по АБ Тесту (создали датафрейм с полученными данными и выгрузили в Excel).
<p>
**<p> Выводы (итоги):<p>**  
<ol> АБ тест проанализирован, результирующий даьафрейм выгружен в Excel, где был создан калькулятор, с помощью которого можно рассчитать какие финансовые результаты му получим при использовании контрольной и тестовой версий.
</ol>
  
  <br>

## Контактная информация
- Email: ss.github1551@mail.ru


