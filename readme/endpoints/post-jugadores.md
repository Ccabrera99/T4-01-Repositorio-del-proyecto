# Endpoint: `POST /jugadores`

Permite añadir un nuevo jugador a la coleccion de jugadores.

## Ejemplo de Solicitud
```http
POST http://localhost:1337/api/jugadores
```
```json
{
    "data":{
        "correo":"jugador@example.com"
    }
}
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 2,
        "attributes": {
            "correo": "jugador@example.com",
            "createdAt": "2023-12-15T07:36:19.989Z",
            "updatedAt": "2023-12-15T07:36:19.989Z",
            "publishedAt": "2023-12-15T07:36:19.987Z"
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

- Asegurate de incluir los parametros adecuados para agregar el jugador.
