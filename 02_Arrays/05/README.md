# IBGE

Você foi contratado pelo IBGE para criar um programa que irá auxiliar na análise de dados da população da maravilhosa Turmalina, cidade do norte de Minas Gerais.

Para isso, você deve criar uma função que recebe um array chamado `dados` com a seguinte estrutura

```js script
dados = [
  ["A", 1550, 1800, 3000, 25000],
  ["J", 6000, 8800, 5000, 2000, 9000, 24000, 800],
  ["I", 150, 10000, 9900]
]
```
em que o primeiro elemento do array que é item do array `dados` é um caracter que informa a faixa etária:
- "A": adulto,
- "J": jovem,
- "I": idoso;

e as demais posições informam os salários, de cada indivíduo, colotados pelo IBGE para aquela população da faixa etária em questão.

No exemplo acima, o primeiro item de `dados` é um array que contém salários da população adulta, o segundo elemento salário da população jovem e o terceiro o salário da população idosa.


**Observação: nem sempre a população adulta será passada no primero índice do array `dados`, a jovem no segundo e a idosa no terceiro. Além disso, repare que a população das diferentes faixas etárias nem sempre terão o mesmo tamanho.**
