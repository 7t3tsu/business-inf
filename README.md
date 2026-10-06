namespace Task1_1; 
    internal class Program
    {
        static void Main(string[] args)
        {
        // Задание 1
            const double a = 1;
            const double b = 2;
            const double c = 0.5;
            const double x = 3;

        double chisl1 = a * Math.Abs(Math.Pow(x, 2) - 4) + (3.0 / 2.0) * b * Math.Log(Math.Abs(x) + 1) + c * Math.Pow(x, 3);
        Console.WriteLine($"Задание 6: y = {chisl1}");
        }
        
    }
