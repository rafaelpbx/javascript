# ES6
**Default value**
```js
function somar(x, y = 1) 
{
    return x + y;
}
console.log("minha soma é: " + somar(5)); 

// saida -> minha soma é: 6

```

**Default value + arrow function**
```js
const somar = (x , y = 2) => x + y;
console.log(somar(5));

// saida -> minha soma é: 6
```