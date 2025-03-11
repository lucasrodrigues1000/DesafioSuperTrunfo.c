#include <stdio.h>



int main() {



    // Super Trunfo



    char estado, estado2;

    char codigo [10], codigo2 [10];

    char cidade [20], cidade2 [20];

    int populacao, populacao2;

    float area, area2;

    float Pib, Pib2;

    int pontosTuristicos, pontosTuristicos2;





    // Carta 1



    printf ("Digite a letra do estado (A-H):\n");

    scanf ("%c", &estado);



    printf ("Codigo:\n");

    scanf ("%s", codigo);



    printf ("Nome da cidade:\n");

    scanf ("%s", cidade);



    printf ("População:\n");

    scanf ("%d", &populacao);



    printf ("Area:\n");

    scanf ("%.2f", &area);



    printf ("PIB:\n");

    scanf ("%.2f", &Pib);



    printf ("Quantidade de pontos Turisticos:\n");

    scanf ("%d", &pontosTuristicos);



    // Informações Carta 2



    printf ("Digite a letra do estado (A-H):\n");

    scanf ("%c", &estado2);

   

    printf ("Codigo:\n");

    scanf ("%s", codigo2);



    printf ("Nome da cidade:\n");

    scanf ("%s", cidade2);



    printf ("Total de Habitantes:\n");

    scanf ("%d", &populacao2);



    printf ("Area:\n");

    scanf ("%.2f", &area2);



    printf ("PIB:\n");

    scanf ("%.2f", &Pib2);



    printf ("Quantidade de pontos Turisticos:\n");

    scanf ("%d", &pontosTuristicos2);







    printf ("Carta 1!\n");



    printf ("Estado: %c\n", estado);

    printf ("Código: %s\n", codigo);

    printf ("Cidade: %s\n", cidade);

    printf ("Habitantes: %d\n", populacao);

    printf ("Area: %.2f\n", area);

    printf ("PIB: %.2f\n", Pib);

    printf ("Pontos Turisticos: %d\n", pontosTuristicos);



    printf("\n");



    printf ("Carta 2!\n");



    printf ("Estado: %c\n", estado2);

    printf ("Código: %s\n", codigo2);

    printf ("Cidade: %s\n", cidade2);

    printf ("Habitantes: %d\n", populacao2);

    printf ("Area: %.2f\n", area2);

    printf ("PIB: %.2f\n", Pib2);

    printf ("Pontos Turisticos: %d\n", pontosTuristicos2);



 

   return 0;

  }
