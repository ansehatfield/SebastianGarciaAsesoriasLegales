using System;

public class Program
{
    public static void Main()
    {
        // Definir la temperatura en Fahrenheit
        int fahrenheit = 94;

        // Convertir Fahrenheit a Celsius
        decimal celsius = (fahrenheit - 32m) * (5m / 9m);

        // Mostrar el resultado
        Console.WriteLine("The temperature is " + celsius + " Celsius.");
    }
}
