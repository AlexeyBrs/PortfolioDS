## Название

Прогнозирование оттока клиента Банка

## Задача

На основе данных из банка определить клиента, который может уйти

## Используемые библиотеки
pandas python matplotlib scikit-learn

## Общий вывод
Рассмотрел и обработал представленные данные.Использовал метод OHE, чтоб убрать категориальные признаки и избежать дамми ловушку.Один датафрейм декомпозирован на три для подготовки модели. Для решения задачи лучшей стала модель RandomForestClassifier(Случайный лес): f1 модели на тестовой выборке 0.5906, метрика auc_roc=0.8524. Она поможет определить клиента банка, который может уйти.
