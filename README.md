
#include <stdio.h>
int main () {

char nome [100];
int idade;
int ano_atual = 2026;
int ano_nascimento = 0;

scanf("%s", nome);
scanf("%d", &ano_nascimento);
idade = ano_atual - ano_nascimento;


printf("%s, %d", nome, idade);


return 0;
}
