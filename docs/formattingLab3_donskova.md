**жирный текст**
*курсив*
***жирный курсив***
~~зачеркнутый~~
`Console.WriteLine("hello");`

```
string name;
name = Console.ReadLine();
Console.WriteLine(name)
```


# Задание: Комментированная программа на C#
Создайте консольное приложение на C#, которое демонстрирует все форматы
Markdown в комментариях к коду.

## Требования к программе:
1. **Имя файла**: `FormatDemo.cs`
2. **Логика**:
 **-** Запрашивает у пользователя два числа;
 **-** Выполняет их сложение;
 **-** Выводит результаты в форматированном виде.
___
## Пример реализации:
```
Console.Write("введите 1 число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.Write("введите 2 число: ");
double number2 = Convert.ToDouble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"**результаты операций: {sum}**");
```