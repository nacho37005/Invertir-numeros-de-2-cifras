# Invertir-numeros-de-2-cifras
using System;
					
public class Program
{
	public static void Main()
	{
		int AUX, DEC, UNI, NUM;
		string linea;
		
		Console.WriteLine("Ingrese un numero de dos cifras:");
		linea = Console.ReadLine();
		NUM = int.Parse(linea);
		DEC = NUM/10;
		UNI = NUM % 10;
		AUX = (UNI * 10) + DEC;
		Console.WriteLine("El numero invertido es:" + AUX);
		Console.WriteLine("Pulsa una tecla");
		Console.ReadLine();
		
	}
}
