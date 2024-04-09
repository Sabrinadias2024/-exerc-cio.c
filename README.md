#include <stdio.h>
#include <math.h>//Biblioteca necessária para raiz quadrada.

int main(){

	float numero;

	printf("Digite um numero: ");
	fflush(stdout);//Necessário para Bug do Eclipse em Windows
	scanf("%f", &numero);

	if(numero > 0){
		printf("A Raiz Quadrada e %.2f", sqrt (numero));
	}else{
		printf("Numero Invalido");
	}

	return 0;
}
