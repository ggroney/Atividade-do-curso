Problema 

Elabore um algoritmo para calcular o salário líquido de 05 pessoas.
Solicite ao usúario que digite o seu nome e o valor do seu salário bruto.
Peça também para o usuário digitar a quantidade de dependentes.
Para cada um dos dependentes deve ser solicitado o ganho mensal. Este valor deverá ser adicionadoao salário bruto.
Calcule a renda familiar per capta.
Caso a renda para cada membro da família seja menor que R$ 500,00 a pessoa ficará isenta de imposto de renda, ou seja, não será calculado dentre as faixas salariais e seu valor será zero.
Caso a renda para cada membro da família seja maior ou igual a R$ 500,00 o imposto de renda a ser descontado do salário bruto deve considerar as seguintes regras:
* salário bruto (de 0,00 até 1.903,98): 5%
* salário bruto (de 1.903,99 até 2.826.65): 7,5%
* salário bruto (a partir de 2.826,66): 15%
Ao final, mostre na tela o valor do salário líquido.

Armazene os salários líquidos em uma coleção indexada (array).

Depois, calcule a média de todos os salários líquidos.
Posteriormente, mostre a média dos salários líquidos e quantas pessoas estão abaixo desse valor médio.

Refatore o seu código. Para isso, crie 2 funções, a saber:
* função para calcular o IR: esta função deve receber como parâmetros o salário bruto e a renda per capta, e, retornar ao final o valor do IR:
* função para calcular a quantidade de salários líquidos menores que a média: esta função deve receber como parâmetros o array de salários líquidos e a média dos salários líquidos, e, retornar a quantidade de salários líquidos menores que a média;

Versão: 12 - Funções

