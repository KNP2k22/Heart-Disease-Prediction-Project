# Heart-Disease-Prediction-Project

## Обзор
Этот проект направлен на предсказание наличия или отсутствия сердечного заболевания у пациентов на основе различных физических характеристик. Используемый набор данных содержит 14 атрибутов, связанных с физическим тестированием пациентов, таких как возраст, пол, тип боли в груди, давление, уровень холестерина и другие. 
Цель - построить модель классификации, способную точно предсказывать вероятность заболевания сердца на основе этих признаков. 
Источник: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

## Структура проекта
Проект разделен на несколько ключевых этапов:

### Исследование данных и визуализация:

Анализ базовой статистики и характеристик набора данных.
Визуализация распределения целевой переменной с использованием столбчатой диаграммы.
Создание парных графиков для изучения взаимосвязей между выбранными признаками.
Генерация тепловой карты для визуализации корреляций между всеми признаками.

### Машинное обучение:

Разделение данных на обучающий и тестовый наборы.
Нормализация данных признаков с использованием StandardScaler.
Построение и обучение модели логистической регрессии с автоматическим подбором параметров с использованием LogisticRegressionCV.
Оценка производительности модели на тестовом наборе, включая создание матрицы ошибок, отчета классификации и кривых производительности (кривая точности-полноты и кривая ROC).

### Прогноз для нового пациента:

Использование обученной модели для предсказания наличия сердечного заболевания у нового пациента с конкретными значениями признаков.
Отображение результатов предсказания и вероятностей для каждого класса.

## Как использовать
Чтобы запустить и воспроизвести этот проект, следуйте этим шагам:

### Установка зависимостей:

Убедитесь, что у вас установлены необходимые библиотеки. Вы можете установить их с помощью:

pip install numpy pandas seaborn matplotlib scikit-learn

#### Получение файла с данными:

Убедитесь, что у вас есть файл с данными (heart.csv).

### Запуск блокнота Jupyter:

Откройте и выполните блокнот Jupyter (Heart-Disease-Prediction-Project..ipynb) в вашей предпочтительной среде.
