# Endpoint: `DELETE /especies-y-habitats/{id}`

Permite eliminar una especie y habitat mediante su identificador unico.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único de la especie y habitat que se desea elimninar.

## Ejemplo de Solicitud
```http
DELETE http://localhost:1337/api/especies-y-habitats/2
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 2,
        "attributes": {
            "createdAt": "2023-12-15T08:18:30.493Z",
            "updatedAt": "2023-12-15T08:18:30.493Z",
            "publishedAt": "2023-12-15T08:18:30.491Z",
            "especie": "Vigilante"
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

- Asegurate de incluir un ID válido en la solicitud para eliminar la especie y habitat deseada.
