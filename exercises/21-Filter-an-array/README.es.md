# `21` Filter an Array

Otra función sorprendente para los arrays es `array.filter()`. Recorre todo el arreglo original y solo devuelve los valores que coinciden con una condición particular.

[Aquí está la documentación](https://www.w3schools.com/jsref/jsref_filter.asp) de la función `filter()` en w3schools.

Por ejemplo, este algoritmo filtra el arreglo `allNumbers` y devuelve un nuevo arreglo con solo los números impares:

```js
let allNumbers = [23,12,35,5,3,2,3,54,3,21,534,23,42,1];

let onlyOdds = allNumbers.filter(function(number) {
	return (number % 2 > 0)
});

console.log(onlyOdds);
```

## 📝 Instrucciones:

1. Completa el código para que llene el arreglo `resultingNames` solo con los nombres que comienzan con la letra R.

2. Usa la función `array.filter()`.

## 💡 Pista:

+ [Aquí hay un video de 2 min](https://www.youtube.com/watch?v=0qsFDFC2oEE) explicando la función `array.filter()`.
