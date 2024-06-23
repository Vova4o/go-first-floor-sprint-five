## Учебный проект: Фитнес-трекер

### Описание:

Данный проект представляет собой учебный инструмент, предназначенный для изучения основ программирования на языке Go.
Он реализует функции фитнес-трекера, позволяя вычислять различные показатели тренировок,
такие как расстояние, скорость, количество сожженных калорий.

### Цели проекта:

- Ознакомить пользователей с базовыми концепциями языка Go, включая работу с типами данных, операторами, циклами, функциями и интерфейсами.
- Продемонстрировать практическое применение языка Go в решении задач из области обработки данных и вычислений.
- Развить навыки написания читаемого и понятного кода.

### Возможности:

- Подсчет пройденного расстояния за время тренировки.
- Расчет средней скорости движения.
- Оценка количества сожженных калорий с учетом типа тренировки, веса, роста пользователя и других параметров.
- Предоставление информации о тренировке в удобном формате.

### Структура проекта:

- **main.go:** Содержит код основной программы, включая функции для чтения данных, вычисления показателей тренировок и вывода результатов.
- **training.go:** Определяет структуру ```Training```, которая является базовой для всех типов тренировок (бег, ходьба, плавание).
- **running.go:** Определяет структуру ```Running``` и методы для вычисления показателей беговой тренировки.
- **walking.go:** Определяет структуру ```Walking``` и методы для вычисления показателей ходьбы.
- **swimming.go:** Определяет структуру ```Swimming``` и методы для вычисления показателей плавания.

### Использование:

1. **Скачайте проект:** Скачайте архив с кодом проекта и распакуйте его в удобную для вас директорию.
2. **Запустите программу:** Откройте терминал и перейдите в директорию с проектом. Запустите команду ```go run main.go```.
3. **Введите данные о тренировке:** Программа запросит информацию о типе тренировки, продолжительности, количестве шагов, весе пользователя и других параметрах.
4. **Получите результаты:** Программа выведет информацию о тренировке, включая расстояние, скорость, количество сожженных калорий.

### Образовательный аспект:

- **Изучение типов данных:** В проекте используются различные типы данных Go, такие как int, float64, string, time.Duration и др.
- **Работа с операторами:** Продемонстрировано использование арифметических, логичеcких и операторов сравнения.
- **Циклы и условия:** Используются циклы for и if для обработки данных и вывода результатов в зависимости от типа тренировки.
- **Функции:** Определены функции для вычисления показателей каждого типа тренировки.
- **Интерфейсы:** Используется интерфейс CaloriesCalculator для унификации методов вычисления калорий.

### Важное примечание:

Данный проект является учебным и не предназначен для использования
в качестве профессионального фитнес-трекера.
Формулы для вычисления калорий являются приблизительными
и могут не учитывать все индивидуальные особенности пользователя.

### Дополнительно:

- Проект может быть доработан и расширен для добавления новых типов тренировок, функций отслеживания прогресса и других возможностей.
- Изучите код проекта, чтобы лучше понять применение языка Go в задачах обработки данных и вычислений.