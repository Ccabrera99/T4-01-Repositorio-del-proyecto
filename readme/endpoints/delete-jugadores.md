# Endpoint: `DELETE /jugador/{id}`

Permite eliminar un jugador mediante su identificador unico.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único del jugador que se desea elimninar.

## Ejemplo de Solicitud
```http
DELETE http://localhost:1337/api/jugadores/1
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 1,
        "attributes": {
            "correo": "cristian@example.com",
            "createdAt": "2023-12-15T07:21:51.268Z",
            "updatedAt": "2023-12-15T07:21:53.404Z",
            "publishedAt": "2023-12-15T07:21:53.402Z"
        }
    },
    "meta": {}
}
```

## Respuestas de Errores Posibles
- Código 404 Not Found:

```json
{
    "data": null,
    "error": {
        "status": 404,
        "name": "NotFoundError",
        "message": "Not Found",
        "details": {}
    }
}
```

## Notas Adicionales

- Asegurate de incluir un ID válido en la solicitud para eliminar al jugador deseado.
