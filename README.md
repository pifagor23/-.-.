#Выполнить: Вводятся три числа — длины трех сторон треугольника. Создайте функцию Perimeter(), которая вычисляет периметр треугольника по длинам трех его сторон.

using System;
namespace qwe
{
    class Program
    {
        
    static void Perimeter(int a, int b, int c,out int res)
    {
        res=a+b+c;
            return;
    }
    static void Main(string[] args)
        {
            int a, b, c;
            a = int.Parse(Console.ReadLine());
            b = int.Parse(Console.ReadLine());
            c = int.Parse(Console.ReadLine());
            Perimeter(a, b, c, out int res);
            Console.WriteLine(res);
        }
    }
}
