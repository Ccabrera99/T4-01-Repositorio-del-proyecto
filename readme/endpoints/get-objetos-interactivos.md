# Endpoint: `GET /objetos-interactivos`

Recupera la lista de todos los objetos intercativos disponibles.


## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/objetos-interactivos
```
## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": [
        {
            "id": 1,
            "attributes": {
                "createdAt": "2023-12-15T07:23:01.274Z",
                "updatedAt": "2023-12-15T07:23:01.274Z",
                "publishedAt": "2023-12-15T07:24:30.040Z",
                "descripcion": "Abre una caja con material",
                "nombre": "Llave"
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