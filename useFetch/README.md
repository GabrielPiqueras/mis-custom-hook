# Hook - useFetch

Ejemplo:

```js
    const url = 'endpoint de una API';
    const { data, loading, error } = useFetch(url);
```

| Propiedad | Tipo | Descripción |
| ------------- | ------------- | ------------- |
| data  | Object  | Datos recibidos de la petición.  |
| loading | Boolean | Si la petición está cargando o no. |
| error | String | Texto del error. | 
