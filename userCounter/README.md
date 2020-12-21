# useCounter

Hook personalizado para contar un valor de forma positiva (incrementando) o de forma negativa (decrementando) y reiniciar a su valor inicial.

## Ejemplo

```
// Valor inicial del conteo
const valorInicial = 1;

// Llamada del hook y métodos
const [counter, increment, decrement, reset] = useCounter(valorInicial);

```

### Métodos

counter ==> Valor actual del contador       
increment ==> Función que incrementa el counter actual en un valor      
decrement ==> Función que drecementa el counter actual en un valor       
reset ==> Función que reinicia el valor del contador a su estado inicial      
