# useFetch Hook

Ejemplo de uso:
```
    const url = 'endpoint de una API';
    const {data, loading, error} = useFetch(url);
```

Los valores por defecto de las variables son:
```
    data: null,
    loading: true,
    error: null,
```