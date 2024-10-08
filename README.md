# Типы Данных

В Java типы данных можно разделить на примитивные и ссылочные.
Ссылочные типы данных включают объекты и массивы.
Примитивные типы данных представляют собой простые значения, такие как числа и символы. 

## Примитивных типы данных:

1. **byte**: хранит целое число от -128 до 127 и занимает 1 байт.
   ```
   byte b = 100;
   ```

2. **short**: хранит целое число от -32768 до 32767 и занимает 2 байта.
   ```
   short s = 10000;
   ```

3. **int**: хранит целое число от -2147483648 до 2147483647 и занимает 4 байта.
   ```
   int i = 100000;
   ```

4. **long**: хранит целое число от –9 223 372 036 854 775 808 до 9 223 372 036 854 775 807 и занимает 8 байт.
   ```
   long l = 10000000000L;
   ```

5. **float**: хранит число с плавающей точкой от -3.4*1038 до 3.4*1038 и занимает 4 байта.
   ```
   float f = 10.5f;
   ```

6. **double**: хранит число с плавающей точкой от ±4.9*10-324 до ±1.7976931348623157*10308 и занимает 8 байт.
   ```
   double d = 20.99;
   ```

7. **char**: хранит одиночный символ в кодировке UTF-16 и занимает 2 байта, поэтому диапазон хранимых значений от 0 до 65535.
   ```
   char c = 'A';
   ```

8. **boolean**: Логический тип данных хранит true или false.
   ```
   boolean bool = true;
   ```

## Ссылочные Типы Данных

Ссылочные типы данных включают объекты и массив:

1. **String**: Для работы со строками.
   ```
   String str = "Hello, World!";
   ```

2. **Массивы**: Хранит нескольких элементов одного типа данных.
   ```
   int[] numbers = {1, 2, 3, 4, 5};
   ```

## Объявление Переменных

Что бы объявить переменную нужно указать тип данных и имя переменной:
```
int age;
String name;
```

Инициализация переменной происходит при присвоении значения:
```
age = 30;
name = "Alice";
```

Можно объединить объявление и инициализацию:
```
int age = 30;
String name = "Alice";
```
# Ввод Данных

## Ввод и вывод Данных в коде

Для ввода данных в Java можно использовать библиотеку `Scanner`.

```
import java.util.Scanner;       		//Подключение библиотеки

public class Main 
{
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите ваше имя- ");         	//Вывод строки
        String name = scanner.nextLine();               	//Ввод данных

        System.out.print("Введите ваш год рождения- ");     	//Вывод строки
        int age = scanner.nextInt();                        	//Ввод данных

        System.out.println("Привет " + name + ". Вы родились в " + age);    //Ввод всех введеных данных
    }
}
```

## Вывод Данных строки

Для вывода данных в Java можно использовать. 

```System.out.println()		//С новой строки```

```System.out.print()		//На той же строки```



