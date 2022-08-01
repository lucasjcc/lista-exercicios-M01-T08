1. Transforme o array `dados`, mostrado abaixo, em um array de objetos em que cada objeto tenha duas propriedades: `faixaEtaria` e `salarios`.
```js script
dados = [
  ["A", 1550, 1800, 3000, 25000],
  ["J", 6000, 8800, 5000, 2000, 9000, 24000, 800],
  ["I", 150, 10000, 9900]
]
```
2. modifique a propriedade `faixaEtaria` para uma string que mostre o nome completo da faixa etária em questão:
   - "Adulto";
   - "Jovem";
   - "Idoso".
3. Crie uma nova propriedade chamada `mediaSalarial` que armazena a média do salário de cada faixa etária.
4. Ordene esse novo array de tal forma que a faixa etária com a maior média salarial venha no primeiro índice do array `dados`, a segunda maior média no segundo índice e a terceira maior média no terceiro índice.
5. Crie uma nova propriedade chamada `maiorSalario` que armazene o maior salário coletado pelo IBGE de cada uma das faixas salarial.

No final dos 5 passos, seu array deve ter a seguinte "cara":

```js script
dados = [
    {
        faixaEtaria: "Jovem",
        salarios: [6000, 8800, 5000, 2000, 9000, 24000, 800],
        mediaSalarial: 7942.85,
        maiorSalario: 24000
    },
    {
        faixaEtaria: "Adulto",
        salarios: [1550, 1800, 3000, 25000],
        mediaSalarial: 7837.5,
        maiorSalario: 24000
    },
    {
        faixaEtaria: "Idoso",
        salarios: [150, 10000, 9900],
        mediaSalarial: 3300,
        maiorSalario: 24000
    }
]
```

**Lembre-se sempre que o que está sendo mostrado acima é apenas um EXEMPLO.**