# Tamrin-3
using System;

class Program
{
    static void Main()
    {
        Console.Write("یک عدد بین 1 تا 7 وارد کنید: ");
        int number = int.Parse(Console.ReadLine());

        switch (number)
        {
            case 1:
                Console.WriteLine("شنبه");
                break;
            case 2:
                Console.WriteLine("یک‌شنبه");
                break;
            case 3:
                Console.WriteLine("دوشنبه");
                break;
            case 4:
                Console.WriteLine("سه‌شنبه");
                break;
            case 5:
                Console.WriteLine("چهارشنبه");
                break;
            case 6:
                Console.WriteLine("پنج‌شنبه");
                break;
            case 7:
                Console.WriteLine("جمعه");
                break;
            default:
                Console.WriteLine("END");
                break;
        }
    }
}
