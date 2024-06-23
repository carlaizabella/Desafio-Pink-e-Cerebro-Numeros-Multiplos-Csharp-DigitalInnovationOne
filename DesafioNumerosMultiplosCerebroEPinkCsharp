using System;

class minhaClasse
{
    static void Main(string[] args)
    {
        int suavariavel = int.Parse(Console.ReadLine());
        string[] n = Console.ReadLine().Split(' ');

        int multiplo2 = 0;
        int multiplo3 = 0;
        int multiplo4 = 0;
        int multiplo5 = 0;

        for (int iContador = 0; iContador < suavariavel; iContador++)
        {
            int num = int.Parse(n[iContador]);
            if (num % 2 == 0)
                multiplo2++;
            if (num % 3 == 0)
                multiplo3++;
            if (num % 4 == 0)
                multiplo4++;
            if (num % 5 == 0)
                multiplo5++;
        }

        Console.WriteLine($"{multiplo2} Multiplo(s) de 2");
        Console.WriteLine($"{multiplo3} Multiplo(s) de 3");
        Console.WriteLine($"{multiplo4} Multiplo(s) de 4");
        Console.WriteLine($"{multiplo5} Multiplo(s) de 5");
    }
}
