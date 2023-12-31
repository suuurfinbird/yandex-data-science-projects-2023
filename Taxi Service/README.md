#  Прогноз количества заказов такси
## Описание проекта
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Необходимо построить модель для такого предсказания.
## Навыки и инструменты
- pandas
- numpy
- seaborn
- sklearn
- sklearn.model_selection.TimeSeriesSplit
- XGBoost
- CatBoost
- Prophet
- SARIMA
- statsmodels.tsa.seasonal.seasonal_decompose

## Данные
В наличии следующие данные данные:
* num_orders — количество заказов такси
* datetime - временной отрезок
## Выводы
Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей. Проведено исследование трёх типов моделей - линейные, ансамблевые и градиентный бустинг. Протестированы автоматические forecast-модели. Выбрана модель - CatBoost и протестирована на тестовой выборке.
