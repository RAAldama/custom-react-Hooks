# useCounter Hook

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        mail: '',
    };

    const [formValues, handleInputChange, reset] = useForm( initialForm );
```

* Los formValues son los valores del formulario entregado.
* handleInputChange es una función para poder cambiar los valores.
* reset es una función para poder limpiar los campos al enviar información.