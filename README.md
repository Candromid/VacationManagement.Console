# Vacation Management

## Описание проекта
Проект "Vacation Management" представляет собой программу управления отпусками сотрудников компании. Программа автоматически генерирует график отпусков, учитывая ограничения и требования, предъявляемые к отпускам сотрудников.

## Методы

### `Main`
Основной метод программы, инициализирующий словарь отпусков, список сотрудников и осуществляющий генерацию и вывод графика отпусков.

### `GenerateVacations`
Метод, ответственный за генерацию отпусков для каждого сотрудника. Учитывает ограничения по максимальному количеству дней отпуска в году, длительности отпусков, рабочим дням и избегает пересечений отпусков между сотрудниками.

### `GenerateRandomWorkingDay`
Метод, генерирующий случайный рабочий день для начала отпуска. Учитывает только понедельник, вторник, среду, четверг и пятницу.

### `IsVacationPossible`
Метод, проверяющий возможность начала отпуска в указанную дату с заданной длительностью, чтобы избежать пересечений с уже запланированными отпусками.
