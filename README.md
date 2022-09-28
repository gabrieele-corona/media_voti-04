/* 
  file: media_voti.c
  autore: Gabriele Corona
  data: 28/9/22
  classe: 3H
  
  Media di tre voti
  
  Input: tre numeri con la virgola
  Elaborazione: tutte le istruzioni per passare dall'input all'output
  Output: un numero con la virgola 
*/
#include<stdio.h>//printf, scanf
int main()
{
	//dichiariamo le tre variabili di input
	float num1, num2, num3;
	// e output
	float ris;
	
	//Input: tre numeri con la virgola
	//avvalorare input
	printf("Inserisci il primo numero\t");
	scanf("%f", &num1);
	printf("Inserisci il secondo numero\t");
	scanf("%f", &num2);
	printf("Inserisci il terzo numero\t");
	scanf("%f", &num3);
	
	//Elaborazione: tutte le istruzioni per passare dall'input all'output
	//assegna alla variabile ris il risultato dell'espressione num1+num2+num3\3
	ris= (num1+num2+num3)/3;
	
	//Output: un numero con la virgola 
   //visualizza output
   printf("Il risultato della media dei voti e'\t %.2f", ris);
   
   //terminiamo il programma
	return 0;
}

