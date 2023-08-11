// 1. Задайте массив заполненный случайнми положительными трехзначными цифрами, напишите программу,
// которая покажет количество четных чисел в массиве.
[345, 897,568, 234]->2


// Console.WriteLine("Введите размер массива");
// int size = Convert.ToInt32(Console.ReadLine());
// int[] numbers = new int[size];
// FillArrayRandomNumbers(numbers);
// Console.WriteLine("Массив ");
// PrintArray(numbers);
// int count = 0;

// for (int a = 0; z < numbers.Length; a++)
// if (numbers[a] % 2 == 0)
// count++;

// Console.WriteLine($"всего {numbers.Length} чисел, {count} из них чётные");

// void FillArrayRandomNumbers(int[] numbers)
// {
//     for(int i = 0; i < numbers.Length; i++)
//     {
//         numbers[i] = new Random().Next(100,1000);
//     }
// }
// void PrintArray(int[] numbers)
// {
//     Console.Write("[ ");
//     for(int i = 0; i < numbers.Length; i++)
//     {
//         Console.Write(numbers[i] + " ");
//     }
//     Console.Write("]");
//     Console.WriteLine();
// }

// 2. Задайте олномерный массив, заполенный случайными числами. Найдите сумму элементов, стоящих на нечетных позициях.
// [3,7,23,12]->19
// [-4,-6,89,6]->0

// Console.WriteLine("Введите массива");
// int size = Convert.ToInt32(Console.ReadLine());
// int[] numbers = new int[size];
// FillArrayRandomNumbers(numbers);
// Console.WriteLine("Массив: ");
// PrintArray(numbers);
// int sum = 0;

// for (int b = 0; b < numbers.Length; b+=2)
//     sum = sum + numbers[b];

//     Console.WriteLine($"всего {numbers.Length} чисел, сумма элементов на нечётных позициях = {sum}");

// void FillArrayRandomNumbers(int[] numbers)
// {
//     for(int i = 0; i < numbers.Length; i++)
//         {
//             numbers[i] = new Random().Next(1,10);
//         }
// }
// void PrintArray(int[] numbers)
// {
//     Console.Write("[ ");
//     for(int i = 0; i < numbers.Length; i++)
//         {
//             Console.Write(numbers[i] + " ");
//         }
//     Console.Write("]");
//     Console.WriteLine();
// }


// 3. Задайте массив вещественных чисел и найдите разницу между максималдьным и минимальным элементов массива.
// [3 7 22 2 78]->76

// Console.WriteLine("Введите массив");
// int size = Convert.ToInt32(Console.ReadLine());
// double[] numbers = new double[size];
// FillArrayRandomNumbers(numbers);
// Console.WriteLine("Массив");
// PrintArray(numbers);
// double min = Int32.MaxValue;
// double max = Int32.MinValue;

// for (int b = 0; b < numbers.Length; b++)
// {
//     if (numbers[b] > max)
//         {
//             max = numbers[b];
//         }
//     if (numbers[b] < min)
//         {
//             min = numbers[b];
//         }
// }

// Console.WriteLine($"всего {numbers.Length} чисел. MAX = {max}, MIN = {min}");
// Console.WriteLine($"Разница = {max - min}");

// void FillArrayRandomNumbers(double[] numbers)
// {
//     for(int i = 0; i < numbers.Length; i++)
//         {
//             numbers[i] = Convert.ToDouble(new Random().Next(100,1000)) / 100;
//         }
// }
// void PrintArray(double[] numbers)
// {
//     Console.Write(" ");
//     for(int i = 0; i < numbers.Length; i++)
//         {
//             Console.Write(numbers[i] + " ");
//         }
//     Console.Write(" ");
//     Console.WriteLine();
// }
