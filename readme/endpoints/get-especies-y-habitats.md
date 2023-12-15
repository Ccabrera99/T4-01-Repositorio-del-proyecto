# Endpoint: `GET /especies-y-habitats`

Recupera la lista de todos las especies y habitats disponibles.


## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/especies-y-habitats
```
## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": [
        {
            "id": 1,
            "attributes": {
                "createdAt": "2023-12-15T07:21:19.624Z",
                "updatedAt": "2023-12-15T07:26:25.554Z",
                "publishedAt": "2023-12-15T07:21:23.000Z",
                "especie": "Merodeador"
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

- Asegurate de escribir correctamente la ruta