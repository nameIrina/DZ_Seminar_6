# DZ_Seminar_6

// Задача 41: Пользователь вводит с клавиатуры M чисел. Посчитайте, сколько чисел больше 0 ввёл пользователь.
// 0, 7, 8, -2, -2 -> 2
// 1, -7, 567, 89, 223-> 3

// Console.Write("Введите числа через пробел: ");

//  int[] array = Console.ReadLine().Split(' ').Select(x => int.Parse(x)).ToArray();

//  int Numbers(int[] array)
//  {
//      int count = 0;

//      for (int j = 0; j < array.Length; j++)
//      {
//          if (array[j] > 0) count++;
//      }
//      return count;
//  }
//  Console.WriteLine(Numbers(array));

//  Задача 43: Напишите программу, которая найдёт точку пересечения двух прямых, заданных уравнениями y = k1 * x + b1, y = k2 * x + b2; значения b1, k1, b2 и k2 задаются пользователем.
// b1 = 2, k1 = 5, b2 = 4, k2 = 9 -> (-0,5; -0,5)

// double X;
// double Y;
// Console.Write("Введите по очереди b1, k1, b2 и k2 одной строкой через пробел: ");
// int[] array = Console.ReadLine().Split(' ').Select(int.Parse).ToArray();
// int a = array [1];
// int b = array [3];
// int c = array [0];
// int d = array [2];

// if (a == b)
// {
//     Console.WriteLine("Прямые с такими параметрами паралельны");
// }
// else
// {
//     X = (double) (d-c)/(a-b);
//     Y = (double) a*(d-c)/(a-b) + c;
//     Console.WriteLine("Точка пересечения двух прямых:");
//     Console.WriteLine($"Х: {X:0.00} Y: {Y:0.00}");
// }

// Задача 42: Напишите программу, которая будет преобразовывать десятичное число в двоичное.
// 45 -> 101101
// 3 -> 11
// 2 -> 10

// Console.WriteLine("Введите число: ");
//  int a = int.Parse(Console.ReadLine());
//  int k;
//  string result = " ";
//  while (a > 0)
//  {
//      k = a % 2;
//      result = k + result;
//      a = a / 2;
//  }
//  Console.WriteLine($"Вывод: {result}");