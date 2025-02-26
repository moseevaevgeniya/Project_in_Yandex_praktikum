## Проект: Анализ пользовательского поведения в мобильном приложении
[ipynb](https://github.com/moseevaevgeniya/-yandex_praktikum/blob/615a1f366c0f93c4557eb29bb414a372da4d0890/9.%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B8/README.md/mobile_app.ipynb) [html](https://github.com/moseevaevgeniya/-yandex_praktikum/blob/824a8db45f3582871fdb1faaf549fc792906f5f9/9.%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B2%20%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B8/README.md/mobile_app.html)
### Описание проекта

Мы работаем в стартапе, который продаёт продукты питания. В процессе проведения анализа перед нами стоит две задачи:

**Первая задача:**  
Изучить воронку продаж. Нам требуется узнать какой путь проходят пользователи до покупки и сколько из них "застревает" на каждом из этапов этого пути.  

**Вторая задача:** 
Дизайнеры решили изменить шрифты в приложении, но учитывая радекальность этого решения, перед его воплощением провели A/A/B-эксперимент. Нам надо изучить его результаты, обратив внимание на идентичность групп A.  
**Нужно разобраться, как ведут себя пользователи мобильного приложения.**  
### Инструменты и навыки  
- Библиотеки: pandas, numpy, scipy, plotly, matplotlib, seaborn;  
- A/B-тестирование; 
- поправка Бомферрони; 
- событийная аналитика;  
- продуктовые метрики;  
- проверка статистических гипотез;  
- визуализация данных.  
### Выводы
##### Вывод по первой задачи:  
Воронка идет по следующему порядку:  
- Зашли на сайт (это самое популярное событие -119101 раз),число пользователей  - 7419, примерно по 2,5 тысячи на группу, доля составила 98,5%;      
- Искали товар по каталогу.На этом втором этапе воронки попадает 62% пользователей, а 38% "теряются по дороге". Это большая цифра и здесь необходимо веб-аналитикам выянить почему так происходит, наверняка есть возможность исправить ситуацию;  
- Добавили в корзину;  
- Оплатили. Пройдя по воронке, до оплаты дошли 6-7% пользователей.
##### Вывод по второй задачи:  
В ходе тестирования были проведены 16 экспериментов.  
В результате всех и каждого A/A/B эксперемента значимой разницы между группами не выявлено. Поэтому можно утверждать, что на поведение пользователей изменение шрифта значимого эффекта не оказало. Тестирование можно назвать успешным - изменение шрифта не повлияло на поведение пользователей.  



