Код_1
1.Зменшення кількості параметрів.
2.Збільшення читабельності та зрозумілості коду.
3.Полегшення обслуговування та внесення змін.
4.Зменшення дублювання коду.
Код_2
1.Окремий клас UserType: Винесено константи типів користувачів в 
окремий клас UserType для кращої організації та уникнення плутанини змінних.
2.Типізація даних: Додано анотації типів для аргументів методу __init__ 
та функції get_user_type_string для покращення читабельності та перевірки типів під час виконання.
3.Документація: Додано рядкові документи (docstrings) для класу User, методу __init__ 
та функції get_user_type_string для пояснення їх призначення та параметрів.
4.Функція get_user_type_string: Створено окрему функцію для отримання текстового представлення типу користувача, 
покращуючи логіку та модульність коду.
5.Перевірка значення типу користувача: Додано перевірку значення user_type у функції get_user_type_string на випадок невідомих типів.