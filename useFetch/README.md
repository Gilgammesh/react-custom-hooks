# useFetch

Hook personalizado para contar un valor de forma positiva (incrementando) o de forma negativa (decrementando) y reiniciar a su valor inicial.

## Ejemplo

```
// Ruta del endpoint o api que queremos consultar (GET)
const url = "https://jsonplaceholder.typicode.com/users";

// Llamada del hook y métodos
const {data, loading, error} = useFetch(url);

```

### Métodos
data  ==>  Objeto en JSON de la respuesta obtenida del endpoint o api
loading  ==>  Estado que indica la obtención de la data (true: "cargando", false: "listo")
error  ==>  Mensaje que se obtiene si hubiese un problema al obtener la data