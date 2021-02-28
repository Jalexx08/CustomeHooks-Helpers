# useForm Hook

Here's an example of usage:

``` javascript
const initialForm = {
    name: '',
    age: 0,
    email: ''
}

const [ formValues, handleInputChange, reset ] = useForm( initialForm )

```