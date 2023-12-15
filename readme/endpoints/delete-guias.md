# Endpoint: `DELETE /jugador/{id}`

Permite eliminar una guia mediante su identificador unico.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único de la guia que se desea elimninar.

## Ejemplo de Solicitud
```http
DELETE http://localhost:1337/api/guias/2
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 2,
        "attributes": {
            "Informacion": "Subir herramientas",
            "createdAt": "2023-12-15T07:50:23.663Z",
            "updatedAt": "2023-12-15T07:51:22.734Z",
            "publishedAt": "2023-12-15T07:50:23.663Z"
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

- Asegurate de incluir un ID válido en la solicitud para eliminar la guia deseada.
