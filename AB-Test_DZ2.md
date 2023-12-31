## Задание 1.

Сделайте приоритезацию гипотез из предыдущего урока с помощью ICE.

| Гипотеза | Impact (влияние) | Confidence (уверенность) | Ease (лёгкость реализации) | ICE Score | Метрика |
| --- | --- | --- | --- | --- | --- |
| Введение купонов на скидку позволит увеличить средний чек, потому что увеличится количество товаров в заказе. | 5 | 6 | 5 | 150 | Средний чек |
| Проведение внезапных распродаж позволит увеличить средний доход от пользователя, потому что увеличится количество заказов за месяц. | 6 | 7 | 6 | 252 | Средний доход от пользователя |
| Уведомление о скидке на отложенный товар позволит увеличить выручку, потому что увеличится количество заказов. | 7 | 8 | 5 | 280 | Конверсия в покупку |
| Усовершенствование системы рекомендаций позволит увеличить средний чек, потому что увеличится количество товаров в заказе. | 8 | 9 | 2 | 144 | Средний чек |

## Задание 2.

Составьте шаблон дизайна эксперимента для гипотезы, которая набрала больше всего баллов в практическом задании предыдущего урока.

**Шаблон дизайна эксперимента**
1. Гипотеза. \
Уведомление о скидке на отложенный товар позволит увеличить выручку, потому что увеличится количество заказов.

2. Что делаем. \
Разрабатываем прототип системы оповещения о скидке на отложенный товар для приложения. Добавляем возможность подключить/отказаться от уведомлений данного типа.

3. На каких пользователях тестируем. \
Тестируем на пользователях, которые установили приложение и подключили уведомление.

4. Ключевые метрики для оценки эксперимента.
    * Процент конверсий в покупку
    * Средний доход от пользователя
    * Процент отказавшихся от уведомления

5. Ожидаемый эффект. \
Скидка на отложенный товар подтолкнет пользователя к принятию решения о покупке, что увеличит процент конверсий. При этом нужно посмотреть изменения среднего дохода от пользователя, который может увеличиться за счет увеличения числа покупок или уменьшиться за счет уменьшения среднего чека. Кроме того смотрим процент отказавшихся от уведомления, как показатель актуальности системы оповещения.

6. План действий в зависимости от результатов эксперимента. \
Если наш эксперимент будет положительным и мы зафиксируем ожидаемое улучшение в ключевых метриках и не посадим добавочные, то дорабатываем систему оповещения, масштабирем ее на пользователей сайта, добавляем варианты уведомлений.\
Если основные метрики падают или растут недостаточно, либо добавочные метрики падают, откатываем эксперимент.



