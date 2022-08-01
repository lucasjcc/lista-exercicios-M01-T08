Dada a string abaixo:

```js script
texto = " Luscas defw xqwcw   cqwcwqwq cqwPEDSE Camila  pkpoxkwqxm   RICArdo "
```

1. Retire os espaços em branco do começo e final da string.
2. Coloque cada pedaço, separado por " ", em um array.
3. Exclua deste array espaços em branco.
4. Sabendo que palavras da língua portuguesa tem pelo menos uma vogal (a,e,i,o,u), diga quantas palavras podem ser da nossa língua.
5. Conte a quantidade de palavras que têm mais de 3 letras.
6. Monte uma nova string com o array resultado das operações acima.
7. Crie uma função chamada `filtro` que recebe dois parâmetros: a string `texto` e uma outra string `textoProcurado`. Essa função deve retornar se o `textoProcurado` existe dentro da string `texto`.
   
**Observação: use o método para transformar a string texto e a string textoProcurado em maíusculo (ou minúsculo) para que sua função se torne não sensitiva a letras maúsculas (ou minúsculas).**

## Exemplo
```js script
texto = " Luscas defw %$## xqwcw   cqwcwqwq cqwPEDSE Camila  pkpoxkwqxm   RICArdo "
textoProcurado = "CAMILA"
```

A string `textoProcurado` existe dentro da string `texto`, apesar de nem todo caracter na string `texto` estar em maiúsculo.
