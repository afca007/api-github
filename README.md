# Api Github

Obtener los datos de un usuario introducido por parametro

## Instrucciones de uso

```
npm instal api-github-query
```

### Uso

```
cons api = require('api-github-query');
obtenerDatosDeUsuario(usuario).then(respuesta => console.log(respuesta)).catch(error => console.log(error));
```