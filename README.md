%%writefile teste.cpp
#include 
/*
Programa que calcula a média aritmética
Obter as 2 notas de provas
Calcular a média aritmética
Se a média for igual ou maior que 7, o aluno foi aprovado
senão ele foi reprovado
*/
int main(void) {
    //declaração de variável
    float nota1, nota2, media;

    //Obter as 2 notas de provas
      printf("Digite a primeira nota: ");
      scanf("%f", &nota1);

      printf("Digite a segunda nota: ");
      scanf("%f", &nota2);

    //Calcular a média aritmética
      media = (nota1 + nota2)/2;

    //mostro o resultado
    if (media >= 7 )
      printf("Aprovado! \n");
    else
      printf("Reprovado! Estude mais! \n");

    return 0;
}
     
Overwriting teste.cpp

! g++ teste.cpp -o testec
     

! ./testec
     
Digite a primeira nota: 6
Digite a segunda nota: 6
Reprovado! Estude mais! 

! g++ teste.cpp -o testec
     

! ./testec
     
Digite a primeira nota: 8
Digite a segunda nota: 8
Aprovado! 
