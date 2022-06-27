#include<stdio.h>

int main() {
float salario,novo_salario,diferenca_sal;
printf("Digite o valor do salario: ");
scanf("%f",&salario);
novo_salario=salario+(salario*0.25);
diferenca_sal=novo_salario-salario;
printf("\n Salario antigo = %.2f",salario);
printf("\n Novo Salario = %.2f",novo_salario);
printf("\n A diferenca entre os salario eh de R$ %.2f",diferenca_sal);
} 
else {
novo_salario=salario+(salario*0.;25);
diferenca_sal=novo_salario-salario;
printf("\n Salario antigo = %.2f",salario);
printf("\n Novo Salario = %.2f",novo_salario);
printf("\n A diferenca entre os salario eh de R$ %.2f",diferenca_sal);
}
else {
novo_salario=salario+(salario*0.15);
      diferenca_sal=novo_salario-salario;
printf("\n Salario antigo = %.2f",salario);
      printf("\n Novo Salario = %.2f",novo_salario);
      printf("\n A diferenca entre os salario eh de R$ %.2f",diferenca_sal);
    }
  return 0;
}     
