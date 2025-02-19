## [Проект урока 4. ««Анализ данных о поездках на такси в Перу»»](https://github.com/ElenaAnalyst/data-analysis-homeworks/blob/main/HW1_basic_python/4_lesson/4_lesson_HW.ipynb)

В этом проекте я работаю с данными по поездкам на такси.

### Выполненные задачи:

- Анализ данных;
- Визуализация;
- Сравнение оценок водителей и пассажиров;
- Определение самого опаздывающего водителя и причин его опозданий с помощью гипотез;
- Анализ годовой и недельной сезонности заказов;
- Рассчет и анализ метрики MAU.

<hr>

Данные разделены на три датасета: в [`passengers`](https://github.com/ElenaAnalyst/data-analysis-homeworks/blob/main/HW1_basic_python/4_lesson/4_lesson_passengers.csv) информация о поездках со стороны пассажиров, в [`drivers`](https://github.com/ElenaAnalyst/data-analysis-homeworks/blob/main/HW1_basic_python/4_lesson/4_lesson_drivers.csv) — об этих же поездках со стороны водителей, в [`taxi_2`](https://github.com/ElenaAnalyst/data-analysis-homeworks/blob/main/HW1_basic_python/4_lesson/4_lesson_taxi_2.csv) — и та, и та информация, но о других поездках. В каждой строке каждого датасета — запись об одной поездке.

### Описание данных:

**Passengers** - информация о поездках со стороны пассажиров:

- `journey_id` - уникальный id поездки;
- `driver_score` – какую оценку клиент поставил водителю;
- `user_id` – id пользователя;
- `start_type` – тип заказа (asap, reserved, delayed);
- `start_lat` – исходное местоположение пользователя, широта;
- `start_lon` – исходное местоположение пользователя, долгота;
- `source` – платформа, с которой сделан заказ; 
- `driver_score` – какую оценку клиент поставил водителю.

**Drivers** - информация о поездках со стороны водителей:
   
- `journey_id` - уникальный id поездки;
- `driver_id` – id водителя;
- `taxi_id` – id машины;
- `icon` – тип поездки;
- `start_at` – время начала поездки;
- `end_at` – время окончания поездки;
- `end_lat` – итоговое местоположение, широта;
- `end_lon` – итоговое местоположение, долгота;
- `end_state` – состояние заказа;
- `driver_start_lat` – исходное местоположение водителя, широта;
- `driver_start_lon` – исходное местоположение водителя, долгота;
- `arrived_at` – время прибытия водителя; 
- `rider_score` – какую оценку водитель поставил клиенту.
  
