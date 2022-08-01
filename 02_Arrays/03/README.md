# Controle de treino

Você foi contratado pela Nike para implementar uma nova funcionalidade ao aplicativo de treino da empresa que mostre ao atleta se o redimento que ele está tendo é ou não satisfatório.

O índice de rendimento do atleta é calculado à partir do seguinte cálculo:

$índice (\%) = \frac{treinos ~ concluídos}{quantidade ~ de ~ treinos} \cdot 100$

Você deve criar uma função chamada `calcularRendimento` que recebe dois parâmetros:
- `treinos`: array em que cada posição tem o valor de `true` caso o atleta tenha concluído o treino daquele dia, ou `false` caso não tenha concluído;
- `rendimentoEsperado`: variável numérica que indica o rendimento que o atleta colocou como meta (em porcentagem).

Essa função deve calcular o rendimento e, em seguida, chamar uma outra função chamada `verificarRendimento`. Essa função deve receber o rendimento esperado pelo atleta e o rendimento que ele está tendo e imprir na tela um aviso:
- "Rendimento satisfatório" ou 
- "Rendimento não satisfatório".

*Pessoal, observem que vocês não devem se apegar ao fato do valor do rendimento esperado estar em porcentagem, já que, se vocês seguirem a fórmula dada, o valor do índice também estará em porcentagem.*

## Exemplo

```js script
treinos = [true, false, true, true, true]
rendimentoEsperado = 80
```
No exemplo acima, o atleta obteve o rendimento de

$rendimento (\%) = \frac{4}{5} \cdot 100 = 80$

Como o atleta colocou como meta um rendimento de 80%, ele conseguiu, mesmo que "em cima da risca", obter um rendimento satisfatório.

