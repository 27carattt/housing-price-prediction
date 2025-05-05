
# 🏠 Housing Price Prediction (California Housing)

Проект по предсказанию медианной стоимости жилья в Калифорнии с использованием машинного обучения (Random Forest Regressor).

---

## 🎯 Цель проекта

- Построить модель регрессии для предсказания цен на жильё
- Выявить важнейшие признаки, влияющие на цену
- Оценить точность модели

---

## 🛠️ Используемые технологии

- Python (pandas, seaborn, matplotlib)
- scikit-learn (RandomForestRegressor, train_test_split, metrics)
- Встроенный датасет California Housing (`sklearn.datasets`)

---

## 📊 Этапы проекта

1. **Загрузка данных**
   - Использован встроенный набор California Housing
2. **Анализ данных**
   - Проверка на пропуски
   - Корреляционный анализ
3. **Модель**
   - Использован Random Forest Regressor
   - Метрики: MSE, R²
4. **Интерпретация**
   - Построение графика важности признаков

---

## ✅ Результаты

- R² модели: около 0.80
- Главные факторы, влияющие на цену жилья:
  - `MedInc` — средний доход
  - `AveRooms` — среднее число комнат
  - `HouseAge` — возраст дома

---

## 📁 Как запустить

1. Скачайте Jupyter Notebook: [`housing_price_prediction.ipynb`](./housing_price_prediction.ipynb)  
2. Откройте в [Jupyter Notebook](https://jupyter.org/) или [Google Colab](https://colab.research.google.com/)  
3. Запустите все ячейки

---

## 🔍 Возможные улучшения

- Добавить подбор гиперпараметров (GridSearchCV)
- Протестировать другие модели (XGBoost, Linear Regression)
- Преобразовать признаки (логарифмирование, стандартизация)

---

