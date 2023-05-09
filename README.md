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

> <a href="https://drive.google.com/file/d/12UwVUDgC13FbbJDPhUpO264Nn5s0R3-f/view?usp=share_link"> Калькулятор юнит-экономики</a>
  <a href="https://drive.google.com/file/d/1U2FoauPOKmtlxcdQ6UHel6HjtxDQapZm/view?usp=share_link"> Визуализация </a>
   <a href="https://drive.google.com/file/d/1po30kEQY8YQTaqZrFCY4mJZhkpjH2A0b/view?usp=share_link"> Расчет метрик </a>
  <a href="https://docs.google.com/spreadsheets/d/14BERMd15lGfbqEqaykuePbSlMUhjvy_C/edit?usp=share_link&ouid=105151305661316276071&rtpof=true&sd=true"> Проект 2 </a>
    
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
  
> <a href="https://drive.google.com/drive/folders/1iSmB7q-fJCvcqppuolo8jYaTr2XASQI7?usp=share_link"> Результат, визуализация, код</a>
 
**<p> Выводы (итоги):<p>**  
<ol> Изменения балансов посчитаны, таблица создана, визуализация построена, гипотезы выдвинуты.
</ol>

<br>



