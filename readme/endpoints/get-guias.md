# Endpoint: `GET /guias`

Recupera la lista de todos las guias disponibles.


## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/guias
```
## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": [
        {
            "id": 1,
            "attributes": {
                "Informacion": "Subir nivel",
                "createdAt": "2023-12-15T07:21:33.526Z",
                "updatedAt": "2023-12-15T07:21:40.675Z",
                "publishedAt": "2023-12-15T07:21:40.673Z"
            }
        },
        {
            "id": 2,
            "attributes": {
                "Informacion": "Subir herramientas",
                "createdAt": "2023-12-15T07:50:23.663Z",
                "updatedAt": "2023-12-15T07:51:22.734Z",
                "publishedAt": "2023-12-15T07:50:23.663Z"
            }
        },
        {
            "id": 3,
            "attributes": {
                "Informacion": "Subir equipo",
                "createdAt": "2023-12-15T07:50:31.466Z",
                "updatedAt": "2023-12-15T07:50:45.312Z",
                "publishedAt": "2023-12-15T07:50:31.465Z"
            }
        }
    ],
    "meta": {
        "pagination": {
            "page": 1,
            "pageSize": 25,
            "pageCount": 1,
            "total": 3
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