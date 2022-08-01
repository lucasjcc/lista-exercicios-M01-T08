# Cálculo da nota total

Você foi contratado por uma empresa que aplica provas de concursos para desenvolver um programa que cálcula a nota total que um candidato tirou na prova de múltipla escolha (famosa "prova de marcar"). 

Crie uma função chamada `calcularNota` que recebe dois parâmetros:
- `marcadas`: um array de strings contendo as questões marcadas pelo candidato. Esse array contém, em cada posição, "A", "B", "C" ou "D", dependendo do que o candidato marcou na questão;
- `gabarito`: um array de strings contendo o gabarito da prova (as questões corretas).

Cada questão que o candidato acerta ele ganha um ponto; cada erro, perde um ponto.

*Lembre-se, quando for testar sua função, que os dois arrays devem ter os mesmo tamanhos.*

## Exemplo
```js script
marcadas = ["A", "B", "B", "D", "A", "C"]
gabarito = ["B", "B", "C", "D", "A", "C"]
```
No exemplo acima, o candidato:
- acertou as questões 2, 4, 5, 6
- errou as questões 1 e 3

Portanto, sua pontuação (nota) foi 4 - 2 = 2.