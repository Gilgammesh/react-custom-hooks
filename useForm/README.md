# useForm

Hook personalizado para almacenar los valores escritos en los inputs de un formulario, retornar los valores del formulario como un objeto y resetear a sus valores iniciales.

## Ejemplo

```
// Valores iniciales del formulario
const initialForm = {
    nombres: '',
    apellidos: '',
    email: ''
};

// Llamada del hook y métodos
const [formValues, handleInputChange, resetForm] = useForm(initialForm);

```
### Métodos
formValues  ==>  Objeto con los valores del formulario actual

handleInputChange ==>  Función que cambia los estados de los inputs del formulario

resetForm ==>  Función que resetea los estados de los inputs a sus valores iniciales
