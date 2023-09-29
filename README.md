# una-lista-02-csharp-202302
using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o primeiro número: ");
        double num1 = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o segundo número: ");
        double num2 = Convert.ToDouble(Console.ReadLine());

        double media = (num1 + num2) / 2;

        Console.WriteLine($"A média aritmética é: {media}");
    }
}

using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o valor do produto: ");
        double precoOriginal = Convert.ToDouble(Console.ReadLine());

        double novoPreco = precoOriginal * 1.10;

        Console.WriteLine($"Novo valor do produto: {novoPreco:F2}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe a temperatura em graus Fahrenheit: ");
        double temperaturaFahrenheit = Convert.ToDouble(Console.ReadLine());

        double temperaturaCelsius = (temperaturaFahrenheit - 32) / 1.8;

        Console.WriteLine($"Temperatura em graus Celsius: {temperaturaCelsius:F2}");
    }
}


using System;
