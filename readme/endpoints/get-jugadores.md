# Endpoint: `GET /jugadores`

Recupera la lista de todos los jugadores disponibles.


## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/jugadores
```
## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": [
        {
            "id": 1,
            "attributes": {
                "correo": "cristian@example.com",
                "createdAt": "2023-12-15T07:21:51.268Z",
                "updatedAt": "2023-12-15T07:21:53.404Z",
                "publishedAt": "2023-12-15T07:21:53.402Z"
            }
        }
    ],
    "meta": {
        "pagination": {
            "page": 1,
            "pageSize": 25,
            "pageCount": 1,
            "total": 1
        }
    }
}
```

## Respuestas de Errores Posibles
- Código 404 Not Found:

```json
{
  "error": {
      "status": 404,
      "name": "NotFoundError",
      "message": "Not Found",
      "details": {}
  }
}
```

## Notas Adicionales

- Asegurate de escribir correctamente la ruta.