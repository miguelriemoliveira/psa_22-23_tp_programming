## Aula 1 - Iniciação à programação

Tópicos a abordar:

- Configuração do layout do matlab
- Matlab path
- Matlab help
- Boas práticas, o cabeçalho de um script
- Variáveis, tipos e inicialização
- Funções e scope de variáveis
- Estruturas de dados
    - Vetores
    - Matrizes
    - Listas
    - Estruturas

### Exercício 1.1

Crie uma função chamada psa_combine, que servirá para combinar duas entidades.
A função terá dois argumentos de entrada, e funcionará de forma diferente em função do tipo de variáveis que são dadas na entrada, da seguinte forma:

- Se os argumentos forem ambos do tipo **double**, a função deve retornar o resultado da multiplicação dos valores
- Se os argumentos forem ambos do tipo **int**, a função deve retornar o resultado da soma dos valores
- Se os argumentos forem ambos do tipo **string**, a função deve retornar a concatenação de ambos os textos colocando o valor do primeiro argumento (a), depois um traço, e depois o valor do segundo argumento (b). Por exemplo, se a="viva" e b='psa', o resultado deve ser 'viva-psa'
- Em qualquer outro caso a função deve retornar o valor -1

### Exercício 1.2

Fale com três colegas ao seu lado e faça o levantamento da sua idade e número mecanográfico. Depois faça um programa que guarde esta informação usando os tipos de dados avançados acima descritos. Determine, em função da informação que pretende guardar, o tipo de estrutura de dados mais adequada.

### Exercício 1.3

Volte a falar com os colegas e obtenha também, para cada um deles, o seu nome e local de origem. Acrescente ao seu programa esta nova informação.
A estrutura de dados escolhida no exercício anterior mantém-se?

### Exercício 1.4

Crie um programa que analise os dados criados e imprima o nome e a proveniência da pessoa com o número mecanográfico menor.
