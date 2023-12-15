# Endpoint: `DELETE /objetos-interactivos/{id}`

Permite eliminar un objeto interactivo mediante su identificador unico.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único del objeto interactivo que se desea elimninar.

## Ejemplo de Solicitud
```http
DELETE http://localhost:1337/api/objetos-interactivos/1
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 1,
        "attributes": {
            "createdAt": "2023-12-15T07:23:01.274Z",
            "updatedAt": "2023-12-15T07:23:01.274Z",
            "publishedAt": "2023-12-15T07:24:30.040Z",
            "descripcion": "Abre una caja con material",
            "nombre": "Llave"
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

- Asegurate de incluir un ID válido en la solicitud para eliminar un objeto interactivo.
