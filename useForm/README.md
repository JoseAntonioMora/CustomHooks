# useForm Hook

useFectch() // recibe un valor por defecto y regresa un _state_

Ejemplo de uso:
```
const initialForm = {
    name: '',
    age: 0,
    email: ''
}

const [ formValues, handleInputChnage, reset ] = useForm(initialForm);
```
