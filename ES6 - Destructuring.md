# ES6
**Destructuring**
Arrays
```js
    meuArray = [1,2,3];
    const [a,b,c] = meuArray;

    console.log(a);  // saída será: 1
    console.log(b);  // saída será: 2
    console.log(c);  // saída será: 3
```

Objetos
```js
    meuObjeto = { nome: "Rafael", sobrenome: "Oliveira" };
    const { nome, sobrenome } = meuObjeto;

    console.log(nome);      // saída será: Rafael
    console.log(sobrenome); // saída será: Oliveira
```