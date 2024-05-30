# hr_analytics

# HR аналитика: предсказание уровня удовлетворенности сотрудника и возможное увольнение

## Примененные библиотеки и технологии
- Pandas, pipeline, matplotlib, phik, DecisionTreeRegressor, LinearRegression, KNeighborsClassifier, RandomizedSearchCV

## Цели и задачи проекта
HR-аналитики компании «Работа с заботой» помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают, как избежать финансовых потерь и оттока сотрудников. В этом HR-аналитикам пригодится машинное обучение, с помощью которого получится быстрее и точнее отвечать на вопросы бизнеса.
Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании. Эту информацию получили из форм обратной связи: сотрудники заполняют тест-опросник, и по его результатам рассчитывается доля их удовлетворённости от 0 до 1, где 0 — совершенно неудовлетворён, 1 — полностью удовлетворён. 
Собирать данные такими опросниками не так легко: компания большая, и всех сотрудников надо сначала оповестить об опросе, а затем проследить, что все его прошли. 
У вас будет несколько задач. Первая — построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. 
Почему бизнесу это важно: удовлетворённость работой напрямую влияет на отток сотрудников. А предсказание оттока — одна из важнейших задач HR-аналитиков. Внезапные увольнения несут в себе риски для компании, особенно если уходит важный сотрудник.
Ваша вторая задача — построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

Мною были решены следующие **задачи**:
- Предобработка и изучение данных, исследовательский анализ данных;
- Подготовка данных, признаков в пайплайне;
- Обучение моделей LinearRegression, DecisionTreeRegressor, KNeighborsClassifier и подбор гиперпараметров с помощью RandomizedSearchCV;
- Проверка качества лучшей модели на тестовой выборке с помощью пользовательской метрики (SMAPE).
