# Hook - useForm

Ejemplo:

```js
    const initialForm = {
        name: '',
        edad: '',
        email: ''
    }

    const [ formValues, handleInputChange, resetForm ] = useForm(initialForm);
```

| Propiedad | Tipo | Descripción |
| ------------- | ------------- | ------------- |
| formValues | Object | Objeto que guarda los name de cada input con sus respectivos valores. |
| handleInputChange | Function | Función que se ejecuta cada vez que cambia el valor de un input, recibe el target del input y actualiza su valor correspondiente en el estado formValues |
| resetForm | Function | Reinicia el formulario con el initialForm utilizado. |