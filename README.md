# Lab_6
1. Створіть клас MyList<T>. Реалізуйте у найпростішому наближенні можливість використання його екземпляра аналогічно екземпляру класу List<T>.
Мінімально необхідний інтерфейс взаємодії з екземпляром повинен включати метод додавання елемента, індексатор для отримання значення елемента за вказаним індексом та властивість тільки для читання для отримання загальної кількості елементів.


2. Створіть клас MyDictionary <TKey, TValue>. Реалізуйте у найпростішому наближенні можливість використання його екземпляра аналогічно екземпляру класу Dictionary.
Мінімально необхідний інтерфейс взаємодії з екземпляром повинен включати метод додавання пар елементів, індексатор для отримання значення елемента за вказаним індексом та властивість тільки для читання для отримання загальної кількості пар елементів.


3. Створіть метод, що розширює: public static T[] GetArray(this MyList<T> list). Застосуйте метод, що розширює, до екземпляра типу MyList<T>, розробленого в завданні 1. Виведіть на екран значення елементів масиву, який повернув метод GetArray().


4. Створіть клас MyClass, що містить статичний фабричний метод – T FacrotyMethod(), який породжуватиме екземпляри типу, зазначеного як параметр типу (Т).
