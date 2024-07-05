# Tabuada-de-Multiplicacao
Tabuada de multiplicação básica.

Neste projeto me desafiei a criar um código com o intuito de mostrar a serie de tabuada que o usuario deseja saber. Exemplo : O sebastian recebeu a questão de seu irmão menor aonde diz o seguinte:
Irmão - Mano, quanto que seria a multiplicação de 12 x 11 =?
Dev.Sebastian -  Eu acredito que seria 132, mas para ter a máxima certeza, em vez de contarmos aos dedos, que tal usarmos o programa que seu creiei para saber se estou certo ou não?
Irmão - Bora certificar com o seu programa.

A questão é 12 x 11 = ?

import java.util.Scanner;
public class Tabuada{
    public static void main (String [] args){
             
        Scanner tabuada = new Scanner(System.in);
        
            int numero;
            int multiplicador =1;
            int resultado = 0;
            System.out.println("TABUADA DE MULTIPLICAÇÃO\n");
            
            System.out.println("Digite a serie da tabuada que quer saber,  exemplo : Tabuada de série 2 basta digitar 2 vai aparecer 2*1...: \n");
            numero = tabuada.nextInt();
            
             System.out.println("\nVocê digitou: " + numero  + " segue abaixo a tabela da serie " + numero + "\n");
            
            for (int i = 1; i <= 12; i++){
                int resultadoFinal = numero*i;
            
               
                System.out.println(numero + " x " + i + " = " + resultadoFinal);
                
            }  
            
            
            tabuada.close();  
    }
}

