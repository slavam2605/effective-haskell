Nub
===
Функция, оставляет только уникальные элементы в списке.
Стандартная реализация в Data.List имеет сигнатуру (Eq a) => [a] -> [a]
и работает за O(n^2).
При сигнатуре (Ord a) => [a] -> [a] возможна реализация за O(n log n).
С использованием хэш таблиц можно реализовать за O(n) с сигнатурой (Hashable a) => [a] -> [a].