# ES6
**Map**

> **Nota:**
> - O método **map** interage com cada elemento de um array, chamando uma função de callback e executando determinada lógica descrita no callback. No final, o método retorna um novo array com as modificações.

```js
    arrayNumeros = [1,2,3,4,5,6];
    novoValor = arrayNumeros.map((num) => num * 2);

    console.log(novoValor); // saída será: [2,4,6,8,10,12]
```

**Filter**

> **Nota:**
> - O método **filter** localiza quais elementos satisfazem determinado contexto dentro do array. Por exemplo encontrar nomes com a letra 'a' dentro de um array de nomes.

```js
    nomes = ["Jorge","Carlos","Lucas","Roberto"]
    novoNomes = nomes.filter((nome) => nome.includes("a"));

    console.log(novoNomes); // saída será: [Carlos,Lucas]
```

**Reduce**

> **Nota:**
> - O método **reduce** junta todos os elementos em um só, o reduce reduz todo o array para um elemento ou uma string 

```js
    nomes = ["Jorge","Carlos","Lucas","Roberto"]
    novoNome = nomes.reduce((acumulado, nome) => acumulado + '-' + nome);

    console.log(novoNome);  // saída será:  jorge-carlos-roberto-lucas 
```