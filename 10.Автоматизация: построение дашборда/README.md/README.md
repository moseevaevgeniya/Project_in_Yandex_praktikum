## Проект: Анализ пользовательского взаимодействия с карточками статей в Яндекс.Дзене.Построение дашборда в Tableau Public.
[ipynb](https://github.com/moseevaevgeniya/-yandex_praktikum/blob/d5734cf6c6d4f35dfbc5f51bb5c971a2fdd56683/10.%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F:%20%D0%BF%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0/README.md/%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%20dash_visits.ipynb) [html](https://github.com/moseevaevgeniya/-yandex_praktikum/blob/d5734cf6c6d4f35dfbc5f51bb5c971a2fdd56683/10.%D0%90%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F:%20%D0%BF%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%D0%B0/README.md/%D0%B4%D0%B0%D1%88%D0%B1%D0%BE%D1%80%D0%B4%20dash_visits.html)
### Описание проекта
1. Написать Python-скрипт, который автоматизирует выгрузку данных.  
2. Построить дашборд в Tableau с анализом пользовательского взаимодействия с карточками статей в Яндекс.Дзене.  
3. Ответить на вопросы:  
- Cколько взаимодействий пользователей с карточками происходит в системе с разбивкой по темам карточек?  
- Как много событий генерируют источники с разными темами?  
- Как соотносятся темы карточек и темы источников?  
4. Подготовить презентацию  
### Навыки и инструменты
- Библиотеки: python, SQLAlchemy, pandas;
- PostgreSQL;
- Tableau;
- Продуктовые метрики;
- Построение дашбордов.
### Выводы
1. Мы выяснили: наблюдается два пика активности по 
визитам - небольшой в районе 6:32 РМ по UTC, суммарно примерно 2,5К и 
сильный в районе 6:58 РМ по UTC, суммарно примерно 61К
2. Источник «Семейные отношения» топ-1 источников по генерации карточек 
(10,7%)
3. Источник «Путешествия» хорошо генерирует «Рассказы» (4294 события), а 
источник «Россия» - переходы в карточки «Общество» (3326 события). Источник 
«Кино» также хорошо генерирует переходы в «Науку» (3142 события).
##### [Дашборд в Tableau Public](https://public.tableau.com/authoring/Level_16584398975290/Dashboard1#1)
##### [Презентация](https://disk.yandex.ru/i/a1EwM8ApJfAD2Q)
