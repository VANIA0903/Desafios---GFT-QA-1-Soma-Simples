# Desafios---GFT-QA-1-Soma-Simples
/*
====================================================
Desafios - GFT QA #1
====================================================
1/6 - Distância
====================================================

Desafio
Duas motos (X e Y) partem em uma mesma direção. A moto X sai com velocidade constante de 60 Km/h e a moto Y sai com velocidade constante de 90 Km/h.
Em uma hora (60 minutos) a moto Y consegue se distanciar 30 quilômetros da moto X, ou seja, consegue se afastar um quilômetro a cada 2 minutos.
O seu desafio é ler a distância (em Km) e calcular quanto tempo leva (em minutos) para a moto Y tomar essa distância da outra moto.

Entrada
O arquivo de entrada contém um número inteiro K que representa a quantidade de quilômetro que que a moto Y deve estar da moto X.

Saída
Imprima o tempo necessário para a moto Y ficar com a quantidade K de quilômetro da moto X, seguido da mensagem " minutos".

-----------------------------------------
| Exemplo de Entrada | Exemplo de Saída |
-----------------------------------------
| 30                 | 60 minutos       |
-----------------------------------------
| 110                | 220 minutos      |
-----------------------------------------
/*
====================================================
Desafios - GFT QA #1
====================================================
2/6 - Soma Simples
====================================================

Desafio
Leia dois valores inteiros identificados como variáveis A e B. Calcule a soma entre elas e chame essa variável de SOMA.
A seguir escreva o valor desta variável.

Entrada
O arquivo de entrada contém 2 valores inteiros.

Saída
Imprima a variável SOMA com todas as letras maiúsculas, inserindo um espaço em branco antes e depois do símbolo de igualdade, seguido pelo valor correspondente à soma de A e B.

-----------------------------------------
| Exemplo de Entrada | Exemplo de Saída |
-----------------------------------------
| 30                 | SOMA = 40        |
| 10                 |                  |
-----------------------------------------
| -30                | SOMA = -20       |
| 10                 |                  |
-----------------------------------------
| 0                  | SOMA = 0         |
| 0                  |                  |
-----------------------------------------

SOLUÇÃO ABAIXO: */

import java.io.IOException;
import java.util.Scanner;

public class SimpleSum {
	public static void main(String[] args) throws IOException {
	 	Scanner sc = new Scanner (System.in);
		int A, B, soma;
 		A = sc.nextInt();
		B = sc.nextInt();
 		soma = A+B;
 		System.out.println("SOMA = " + soma);
 		sc.close();
	}
}
