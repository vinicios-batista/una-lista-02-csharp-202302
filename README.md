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

    using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o capital aplicado: ");
        double capital = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe a taxa de juros mensal (em decimal): ");
        double taxaJuros = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o prazo da aplicação em meses: ");
        int prazoMeses = Convert.ToInt32(Console.ReadLine());

        double montante = capital * Math.Pow(1 + taxaJuros, prazoMeses);

        Console.WriteLine($"Montante a ser recebido: {montante:F2}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Número de horas trabalhadas no mês: ");
        double horasTrabalhadas = Convert.ToDouble(Console.ReadLine());

        Console.Write("Valor recebido por hora de trabalho: ");
        double valorHora = Convert.ToDouble(Console.ReadLine());

        Console.Write("Número de filhos com idade menor que 14 anos: ");
        int numFilhos = Convert.ToInt32(Console.ReadLine());

        Console.Write("Valor do salário família por filho: ");
        double salarioFamiliaPorFilho = Convert.ToDouble(Console.ReadLine());

        double salarioBruto = (horasTrabalhadas * valorHora) + (numFilhos * salarioFamiliaPorFilho);

        Console.WriteLine($"Salário bruto a ser recebido: {salarioBruto:F2}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o número: ");
        double numero = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe a base do logaritmo: ");
        double baseLog = Convert.ToDouble(Console.ReadLine());

        double resultado = Math.Log(numero, baseLog);

        Console.WriteLine($"Logaritmo de {numero} na base {baseLog} é: {resultado:F2}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o salário fixo do vendedor: ");
        double salarioFixo = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o valor total das vendas no mês: ");
        double vendasMes = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o percentual de comissão (em decimal): ");
        double comissaoPercentual = Convert.ToDouble(Console.ReadLine());

        double salarioTotal = salarioFixo + (vendasMes * comissaoPercentual);

        Console.WriteLine($"Salário total do vendedor: {salarioTotal:F2}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o total de veículos no estacionamento: ");
        int totalVeiculos = Convert.ToInt32(Console.ReadLine());

        Console.Write("Informe o total de rodas no estacionamento: ");
        int totalRodas = Convert.ToInt32(Console.ReadLine());

        int totalCarros = (totalRodas - (2 * totalVeiculos)) / 2;
        int totalMotos = totalVeiculos - totalCarros;

        Console.WriteLine($"Total de carros: {totalCarros}");
        Console.WriteLine($"Total de motos: {totalMotos}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe a quantidade de segundos: ");
        int segundos = Convert.ToInt32(Console.ReadLine());

        int horas = segundos / 3600;
        int minutos = (segundos % 3600) / 60;
        segundos = segundos % 60;

        Console.WriteLine($"Horas: {horas}, Minutos: {minutos}, Segundos: {segundos}");
    }
}


using System;

class Program
{
    static void Main()
    {
        Console.Write("Informe o primeiro valor: ");
        double valor1 = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o segundo valor: ");
        double valor2 = Convert.ToDouble(Console.ReadLine());

        Console.Write("Informe o terceiro valor: ");
        double valor3 = Convert.ToDouble(Console.ReadLine());

        double mediaAritmetica = (valor1 + valor2 + valor3) / 3;
        double mediaHarmonica = 3 / ((1 / valor1) + (1 / valor2) + (1 / valor3));
        double mediaGeometrica = Math.Pow((valor1 * valor2 * valor3), 1.0 / 3);

        Console.WriteLine($"Média Aritmética: {mediaAritmetica:F2}");
        Console.WriteLine($"Média Harmônica: {mediaHarmonica:F2}");
        Console.WriteLine($"Média Geométrica: {mediaGeometrica:F2}");
    }
}



}


using System;
