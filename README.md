using System;
namespace DiscountCalculator
{
    class Program
    {
        static void Main()
        {
            // pleas enter a number
            Console.Write("pleas enter a number: ");
            double price = Convert.ToDouble(Console.ReadLine());


            // Calculate 15% discount
            double discount = price * 0.15;
            double finalPrice = price - discount;

            // Display final price
            Console.WriteLine("Final price after 15% discount: " + finalPrice);


            Console.ReadKey();
        }
    }
}
