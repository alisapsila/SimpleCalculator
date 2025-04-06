// Импортируем класс Scanner для чтения ввода с клавиатуры
import java.util.Scanner;

 class Main {
    public static void main(String[] args) {
        // Создаем объект Scanner для чтения ввода
        Scanner scanner = new Scanner(System.in);

        // Выводим инструкцию для пользователя
        System.out.println("Введите выражение (например: 3 + 5 или 10-3):");
        System.out.print("> ");  // Приглашение для ввода

        // Читаем всю строку ввода и удаляем ВСЕ пробелы (для унификации)
        String input = scanner.nextLine().replaceAll(" ", "");

        // Разбиваем строку на части. Регулярное выражение ищет операторы (+-*/)
        // и разделяет строку на: [число][оператор][число]
        // Пример: "10-3" → ["10", "-", "3"]
        String[] parts = input.split("(?<=[-+*/])|(?=[-+*/])");

        // Проверяем, что получилось ровно 3 элемента (число, оператор, число)
        if (parts.length != 3) {
            System.out.println("Ошибка: введите 'число оператор число' (пример: 5+3 или 10 - 2)");
            return;  // Завершаем программу при ошибке
        }

        try {
            // Пробуем преобразовать первую часть в целое число
            int a = Integer.parseInt(parts[0]);
            // Запоминаем оператор (вторая часть)
            String op = parts[1];
            // Пробуем преобразовать третью часть в целое число
            int b = Integer.parseInt(parts[2]);

            // Проверяем, что числа в диапазоне 1-10
            if (a < 1 || a > 10 || b < 1 || b > 10) {
                System.out.println("Ошибка: числа должны быть от 1 до 10");
                return;
            }

            // Переменная для результата
            int result;

            // Выбираем операцию в зависимости от введенного оператора
            switch (op) {
                case "+":
                    result = a + b;  // Сложение
                    break;
                case "-":
                    result = a - b;  // Вычитание
                    break;
                case "*":
                    result = a * b;  // Умножение
                    break;
                case "/":
                    result = a / b;  // Деление (целочисленное)
                    break;
                default:
                    // Если оператор не распознан
                    System.out.println("Ошибка: неподдерживаемая операция " + op);
                    return;
            }

            // Выводим результат
            System.out.println("Результат: " + result);

        } catch (NumberFormatException e) {
            // Если введены не числа
            System.out.println("Ошибка: введите целые числа (пример: 7 * 2)");
        }
    }
}
