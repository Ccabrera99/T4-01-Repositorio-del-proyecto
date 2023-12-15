# Endpoint: `POST /guias`

Permite añadir una nueva guia a la coleccion de guias.

## Ejemplo de Solicitud
```http
POST http://localhost:1337/api/guias
```
```json
{
    "data":{
        "Informacion":"Crear libro"
    }
}
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 4,
        "attributes": {
            "Informacion": "Crear libro",
            "createdAt": "2023-12-15T07:52:16.938Z",
            "updatedAt": "2023-12-15T07:52:16.938Z",
            "publishedAt": "2023-12-15T07:52:16.938Z"
        }
    },
    "meta": {}
}
```

## Respuestas de Errores Posibles
- Código 400 Bad Request:

```json
{
    "data": null,
    "error": {
        "status": 400,
        "name": "ValidationError",
        "message": "Missing \"data\" payload in the request body",
        "details": {}
    }
}
```

## Notas Adicionales

- Asegurate de incluir los parametros adecuados para agregar la guia.
