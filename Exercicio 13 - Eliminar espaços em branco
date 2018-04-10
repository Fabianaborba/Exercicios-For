#include <stdio.h>
#include <stdlib.h>
#include <string.h>

void deslocaEsq(char *sVetor, int iIndice){
	for(int i = iIndice; i < strlen(sVetor); i++){
		sVetor[i] = sVetor[i+1];
	}
}

int main(){
	char sVetor[40];
	int i;
	printf("Digite a frase: ");
	fgets(sVetor, 40, stdin);
	sVetor[strlen(sVetor)-1] = '\0';
	
	for(i = 0; i < strlen(sVetor); i++) while (sVetor[i] == ' ') deslocaEsq(sVetor, i);
	
	printf("Frase Modificada: %s", sVetor);
	system("pause>>NULL");
	return 0;
}
