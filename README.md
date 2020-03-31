# Instruções elementares
* Efetuar Operações algébricas básicas;
* Tomar nota de valores;
* Registrar valores;
* Encontrar números primos;
* Associar um valor a outro;
* Distinguir valores maiores e menores;
* Ordenar valores de forma crescente e decrescente;
* Saber quando um número é divisível por outro;
* Checar a ocorrência de valores;


# Algoritmo
1. Tomar nota de todos os n números inteiros positivos;
3. Selecionar todos os números primos menores ou iguais ao maior número anotado;
4. Ordenar os números primos de forma crescente;
5. Selecionar o primeiro primo;
6. Dividir todos os números pelo primo selecionado. 
7. Se o número for divisível pelo primo:

    1. Registrar quantas vezes esse número foi dividido por esse primo em um valor associado a ele;
    2. Anotar o quociente inteiro da divisão no lugar do número.
8. Se o número não for divisível pelo primo:

    1. Não fazer nada com o número e o seu valor associado. 
9. Equanto houver números divisíveis pelo primo, repita 6., senão prossiga para 10;
10. Se houver algum número diferente de 1, selecione o próximo primo e volte para 6;
11. Senão, prossiga para 12;
12. Para cada número entre todos os n:

    1. Adicione 1 a todas os valores associados ao número de vezes dividido por um mesmo primo;
    3. Multiplique todos esses valores;
    2. Tome nota do resultado no lugar do valor associado.
13. Coloque todos os números em ordem decrescente com relação ao valor associado.
14. Devolva o primeiro dos número.
