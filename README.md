# Файл Search.py 
Ищет в рандомном списке заданное пользователем число от 0 до 100 и выводит сообщение:
- Если число отсутствует в рандомном списке: "Cannot find __ in the list"
- Если число было найдено в рандомном списке: "Found __ in index __"
- Если введено не число, то выдаётся ошибка: "Invalid input".

Помимо сообщения так же выводится сам список.

Рандомный список состоит из 10 цифр от 0 до 100, кратные 2-м, отфильтрованный по возрастанию.

## Функция binary_search
1) Определение значения элемента в середине структуры данных. Полученное значение сравнивается с ключом.
2) Если ключ меньше значения середины, то поиск осуществляется в первой половине элементов, иначе — во второй.
3) Поиск сводится к тому, что вновь определяется значение серединного элемента в выбранной половине и сравнивается с ключом.
4) Процесс продолжается до тех пор, пока не будет найден элемент со значением ключа или не станет пустым интервал для поиска.
