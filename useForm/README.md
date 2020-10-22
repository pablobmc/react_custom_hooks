# useForm Hook

Ejemplo:
```
    const initialForm = {
        name: '',
        age: 0,
        email: hola@mail.cl
    }
    
    const [values, handleInputChange, reset] = useForm(initialForm);
```