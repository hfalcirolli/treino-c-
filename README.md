# treino-c-

#include<stdlib.h>
#include<stdio.h>
#include <iostream>



int main(int argc, char** argv) {
	
	float raio,perimetro;
	double pi=3.1415927,area;
	printf("Introduza o raio da circunferencia\n ");
	scanf("%f",&raio);   //introduz o valor do raio digitado pelo usuario.
	area = pi*raio*raio;
	perimetro=2*pi*raio;
	
	printf("Area      = %f\nPerimetro = %f\n",area,perimetro); //mostra os valores calculados.
	getchar();
	
	
	
	return 0;
}
