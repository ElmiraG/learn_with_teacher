Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Необходимо построить модель с предельно большим значением F1-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. 

Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

В проекте использовались модели: RandomForestClassifier, DecisionTreeClassifier и LogisticRegression.
Также использованы две техники балансирования классов Undersampling и Oversamping:

Методы Undersampling:

-функция Downsampling.
-RandomUnderSampler() библиотеки imblearn.
-K-Means, ClusterCentroids() библиотеки imblearn.

Методы Oversamping:

-функция Upsampling.
-RandomOverSampler c shrinkage библиотеки imblearn
-SMOTE() библиотеки imblearn

