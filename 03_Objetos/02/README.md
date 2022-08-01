# Confronto direto

Crie uma função que imprima uma mensagem informando qual time, se é o time A ou o time B, é mais vitorioso em confrontos diretos (quem ganhou mais que quem em jogos em que se enfrentaram).

Sua função vai receber array que tem a seguinte estrutura:

```js script
[
    {
        timeA: 5,
        timeB: 4
    },
    {
        timeA: 3,
        timeB: 3
    },
    {
        timeA: 0,
        timeB: 1
    }
]
```

`No exemplo acima, o time A ganhou o primeiro jogo de 5 a 4, os times empataram o segundo jogo e o time B ganhou o terceiro jogo de 1 a 0.`

Sua função deve imprimir a seguinte mensagem:
- "Time A": caso o time A tenha ganhado mais vezes;
- "Time B": caso o time B tenha ganhado mais vezes;
- "Empate": caso nenhum time tenha ganhado mais que o outro.

**Observação: o array passado acima é apenas um EXEMPLO. Seu programa deve ser generalista o suficiente para receber um array de qualquer tamanho.**

## Exemplo

```js script
[
    {
        timeA: 5,
        timeB: 4
    },
    {
        timeA: 3,
        timeB: 3
    },
    {
        timeA: 2,
        timeB: 1
    },
    {
        timeA: 1,
        timeB: 3
    },
    {
        timeA: 2,
        timeB: 5
    },
    {
        timeA: 0,
        timeB: 1
    }
]
```

No exemplo acima, temos:
- Vitórias do time A: 2
- Vitórias do time B: 3
- Empates: 1

Nesse caso, seu programa deverá mostrar a mensagem "Time B".