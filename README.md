#include <stdio.h>
int main () {

char nome1 [100];
char nome2 [100];
int idade1 , idade2;
int ano_atual = 2026;
int ano_nascimento = 0;

scanf("%s %s", nome1, nome2);
scanf("%d", &ano_nascimento);
idade1= ano_atual - ano_nascimento;
idade2= ano_atual - ano_nascimento;


printf("%s %s, %d %d", nome1, nome2, idade1, idade2);


return 0;
}
