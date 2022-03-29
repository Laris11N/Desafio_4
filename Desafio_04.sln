using System;
using System.Collections.Generic;

namespace Desafio_04
{
	class Program
	{
		

		static void Main(string [] args)
		{
			
			string[] nomes = new string[3];
			nomes[0] = "Larissa";
			nomes[1] = "Marcio";
			nomes[2] = "José";

			int [] idades = new int[3];
			idades[0] = 20;
			idades[1] = 40;
			idades[2] = 18;

			int [] notas = new int [3];
			notas[0] = 10;
			notas[1] = 8;
			notas[2] = 5;

			Console.WriteLine("Dados do Aluno 1: ");
			Console.WriteLine( "nome: " + nomes[0]);
			Console.WriteLine("Idade: " + idades[0]);
			Console.WriteLine("Nota: "+ notas [0]);

			Console.WriteLine();

			Console.WriteLine("Dados do Aluno 2: ");
			Console.WriteLine("nome: " + nomes[1]);
			Console.WriteLine("Idade: " + idades[1]);
			Console.WriteLine("Nota: " + notas[1]);

			Console.WriteLine();

			Console.WriteLine("Dados do Aluno 3: ");
			Console.WriteLine("nome: " + nomes[2]);
			Console.WriteLine("Idade: " + idades[2]);
			Console.WriteLine("Nota: " + notas[2]);

			Console.WriteLine();

			Aluno aluno = new Aluno();

			List<Aluno> listaAluno1 = new List<Aluno>();

			aluno.Nome = "Larissa";
			aluno.Idade = 23;
			aluno.Nota = 10;
			aluno.Nome1 = "Marcio";
			aluno.Idade1 = 40;
			aluno.Nota1 = 8;
			aluno.Nome2 = "José";
			aluno.Idade2 = 18;
			aluno.Nota2 = 5;


			/* Achei que preciva fazer separado, então essa parte descartei
			 
		    List<Aluno> listaAluno2 = new List<Aluno>();
			aluno.Nome1 = "Marcio";
			aluno.Idade1 = 40;
			aluno.Nota1 = 8;

			List<Aluno> listaAluno3 = new List<Aluno>();
			aluno.Nome2 = "José";
			aluno.Idade2 = 18;
			aluno.Nota2 = 5;
			*/

			listaAluno1.Add(aluno);
			

			foreach (Aluno aluno1 in listaAluno1)
			{
				Console.WriteLine("A soma da nota dos alunos é: " + (aluno.Nota + aluno.Nota1 + aluno.Nota2));

			}



			Console.ReadLine();
		} 
	}	
}
/* 1 - Representar o Aluno com classe
Aluno(Nome, Idade, Nota) ok 
2 - Utilizar lista de Alunos com array padrão
Aluno[]alunos = new Aluno[];
3 - Utilizar lista de alunos com objetivo List
List<Aluno> alunos = new List<Aluno>();*/
