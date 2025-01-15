Предсказание оттока клиентов в телекоме

📡 Оператор связи стремится снизить отток клиентов, предлагая промокоды и специальные условия.
Для этого разрабатывается модель, которая будет предсказывать вероятность разрыва договора.
📊 Команда оператора собрала данные о клиентах, тарифах и предоставляемых услугах для анализа.

📋 Описание данных
🗄️ Данные хранятся в базе SQLite и включают следующие таблицы:

Контракт: информация о договоре, тип оплаты, ежемесячные платежи.
Личные данные: пол, возраст, наличие иждивенцев.
Интернет: тип подключения, использование онлайн-безопасности и резервного копирования.
Телефон: подключение дополнительных линий и услуги мультилиний.

🛠️ Этапы работы над проектом
 Загрузка и подготовка данных
 Импорт библиотек: pandas, numpy, seaborn, matplotlib.pyplot, sqlalchemy.
 Загрузка данных из базы SQLite.
 Проверка данных на пропуски и дубликаты.🧐

🔍 Анализ и предобработка данных
Создание итогового признака для предсказаний.
Использование функций для анализа категориальных и количественных данных.
📊 Визуализация распределений: гистограммы, диаграммы размаха.
🧪 Статистическая проверка гипотез
Проверка распределений данных.
📍 Расчет 75% и 98% квантилей.
✂️ Разделение выборок
Подготовка данных для обучения.
Использование train_test_split для выделения обучающей и тестовой выборок.
🤖 Моделирование
🛠️ Обучение модели
Использование алгоритма CatBoost для обучения модели.
📈 Анализ важности признаков.
✅ Тестирование модели
Оценка точности модели на тестовых данных.
Проверка производительности модели.
🧩 Дополнительный анализ
📊 Корреляция Крамера
Построение матрицы корреляций между категориальными признаками.
🔥 Визуализация результатов с помощью тепловой карты.
🔬 Гипотезы
Создание кросс-таблиц для проверки зависимости признаков.
Выполнение хи-квадрат теста для статистического анализа.
🌟 Ансамблевые модели и нейросети
🌐 LightGBM и ансамблирование
Разработка модели LightGBM и ее обучение.
Объединение прогнозов нескольких моделей для создания мета-модели.
🧠 Нейросети
Преобразование данных в формат, пригодный для обучения нейросети.
Обучение модели на основе архитектуры искусственных нейронных сетей.
Оценка точности модели на тестовой выборке.
📢 Выводы и рекомендации
✅ Модель LightGBM продемонстрировала наилучшие результаты по точности на тестовых данных.
📌 Основные рекомендации:

Продвигать долгосрочные подписки среди клиентов.
Внедрить дифференцированный подход для сегментации клиентов и персонализированных предложений.
🎯 Итог: Разработанная модель позволяет предсказывать отток клиентов с высокой точностью и предлагает пути для повышения лояльности абонентов.
