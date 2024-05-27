# Unit-тесты (семинары)
## Урок 6. Юнит тестирование в других языках

Задание 1. Создайте программу на Python или Java, которая принимает два списка чисел и выполняет следующие действия:
a. Рассчитывает среднее значение каждого списка.
b. Сравнивает эти средние значения и выводит соответствующее сообщение:
- ""Первый список имеет большее среднее значение"", если среднее значение первого списка больше.
- ""Второй список имеет большее среднее значение"", если среднее значение второго списка больше.
- ""Средние значения равны"", если средние значения списков равны.

Важно:
Приложение должно быть написано в соответствии с принципами объектно-ориентированного программирования.
Используйте Pytest (для Python) или JUnit (для Java) для написания тестов, которые проверяют правильность работы программы. Тесты должны учитывать различные сценарии использования вашего приложения.
Используйте pylint (для Python) или Checkstyle (для Java) для проверки качества кода.
Сгенерируйте отчет о покрытии кода тестами. Ваша цель - достичь минимум 90% покрытия.

*Формат и требования к сдаче: *
Отчет о выполнении этого задания должен включать в себя следующие элементы:
- Код программы
- Код тестов
- Отчет pylint/Checkstyle
- Отчет о покрытии тестами
- Объяснение того, какие сценарии покрыты тестами и почему вы выбрали именно эти сценарии.

#### Домашняя работа

[Код программы](https://github.com/ShumAhd/Unit---6/tree/main/hw_6/src/main/java/ro/shum)

[Код тестов](https://github.com/ShumAhd/Unit---6/tree/main/hw_6/src/main/java/ro/shum)

![Отчёты Checkstyle и покрытие тестов на скрине](https://github.com/ShumAhd/Unit---6/blob/main/img/2024-01-19_160909.jpg)

#### Объяснение того, какие сценарии покрыты тестами и почему вы выбрали именно эти сценарии.

### Тесты покрывают следующие сценарии:

1.  **`compare_singleElementLists_returnsEqualMessage`**: Этот тест проверяет, что код корректно обрабатывает списки с одним элементом. Это важно, потому что такие списки могут вызвать проблемы в некоторых алгоритмах.

2.  **`testCompareLists_emptyLists_returnsEqualMessage`**: Этот тест проверяет, что код корректно обрабатывает пустые списки. Это крайний случай, который может вызвать проблемы в некоторых алгоритмах.

3.  **`compare_sameAverage_returnsEqualMessage`**: Этот тест проверяет, что код корректно обрабатывает списки с одинаковым средним значением. Это важно, чтобы убедиться, что код правильно определяет, когда средние значения равны.

4.  **`compare_negativeNumbers_correctResult`**: Этот тест проверяет, что код корректно обрабатывает списки с отрицательными числами. Это важно, потому что отрицательные числа могут вызвать проблемы в некоторых алгоритмах.

5.  **`compareLists_firstListHasHigherAverage_returnsFirstListMessage`**: Этот тест проверяет, что код корректно определяет, когда среднее значение первого списка больше среднего значения второго списка.

6.  **`testCompareLists`**: Этот тест проверяет, что код корректно определяет, когда среднее значение второго списка больше среднего значения первого списка.

7.  **`testCompareLists_largeNumbers_correctResult`**: Этот тест проверяет, что код корректно обрабатывает списки с очень большими числами. Это важно, потому что большие числа могут вызвать проблемы в некоторых алгоритмах.

Все эти тесты вместе обеспечивают широкое покрытие различных сценариев использования кода, что помогает убедиться, что он работает правильно во всех этих ситуациях.

