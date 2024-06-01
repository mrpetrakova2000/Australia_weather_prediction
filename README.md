# Модель предсказания погоды в Австралии на основе данных за 10 лет ML
Разработанные модели предсказывают вероятность осадков на основе данных за каждый день с 01-01-2008 по 25-06-2017, представленных набором значений по следующим параметрам:
- локация;
- минимальная температура за день (в гр. Цельсия);
- максимальная температура за день (в гр. Цельсия);
- осадки (в мм);
- испарение;
- УФ-индекс;
- преимущественное направление ветра;
- средняя скорость ветра за день;
- направление ветра в 9 ч. утра и в 3 ч. дня;
- скорость ветра в 9 ч. утра и в 3 ч. дня;
- влажность воздуха в 9 ч. утра и в 3 ч. дня;
- атмосферное давление в 9 ч. утра и в 3 ч. дня;
- уровень облачности в 9 ч. утра и в 3 ч. дня;
- температура в 9 ч. утра и в 3 ч. дня;
- есть ли дождь сегодня (да/нет);
- есть ли дождь завтра (да/нет), отмечено фактическое значение.

  
Проведены 4 этапа анализа данных:
1. Подготовка и нормализация данных.
2. Классификация данных.
3. Кластеризация данных.
4. Регрессия.

На основе представленных моделей возвращается результат, формирующий предсказание дождя на следующий день.
