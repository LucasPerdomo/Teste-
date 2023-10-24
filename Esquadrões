double[,] Esquadroes = new double[3, 2];

int esquadraoVencedor = 0;
double maiorForca = 0;


for (int repetidor = 0; repetidor < 3; repetidor++)
{
    Console.WriteLine($"Esquadrão {repetidor}");
    Console.Write("Digite a força do capitão: ");
    Esquadroes[repetidor, 0] = double.Parse(Console.ReadLine());

    Console.Write("Digite a força do tenente: ");
    Esquadroes[repetidor, 1] = double.Parse(Console.ReadLine());
       double forcaTotal = Esquadroes[repetidor, 0] + Esquadroes[repetidor, 1];
    

    if (forcaTotal > maiorForca)
    {
        esquadraoVencedor = repetidor;
        maiorForca = forcaTotal;
    }

    Console.WriteLine($"Esquadrão {repetidor}: Força Total = {forcaTotal}");
    
}

Console.WriteLine($"Esquadrão vencedor: Esquadrão {esquadraoVencedor}");
