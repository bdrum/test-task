# Описание тестового задания для кандидата

Входные данные:

- Периоды
- Районы, города
- Газовозы (машины)
- Заказы
- Маршруты

|Файл            |Тип         |Описание                   |
|----------------|------------|---------                  |
|Parametres      |input       |параметры                  |
|Cities          |input       |справочник городов         |
|Cars            |input       |справочник машин           |
|Orders          |input       |заявки                     |
|Routes          |input       |доступные маршруты движения|
|ordersMade      |result      |выполнение заявок          |
|runsMade        |result      |выполненные движения       |
|capacityMade    |result      |загрузка машины по периодам|
|OrdersLeft      |остаток     |по невыполненным заявкам   |

Целевая функция:

- Максимизировать операционную прибыль (выручка – затраты)

Ограничения/требования:

- В первом периоде все машины стоят на базе
- В последнем периоде все машины стоят на базе
- В первом периоде все машины пустые
- Загрузка машины возможна только на базе
- Отгрузка по заявке возможна только в нужном районе, городе

Результаты расчета (отчеты):

- Выполнение заявок
- Выполнение перемещений
- Остаток газа в каждом периоде

<details>
Cледить за остатком газа в машине,
допустимым объемом отгрузки каждому клиенту,
нахождением машин по узлам
</details>