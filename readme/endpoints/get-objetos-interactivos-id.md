# Endpoint: `GET /objetos-interactivos/{id}`

Permite obtener información detallada sobre una guia específico mediante su identificador único.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único de los objetos interactivos que se desea recuperar.

## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/objetos-interactivos/1
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
  "error": {
      "status": 404,
      "name": "NotFoundError",
      "message": "Not Found",
      "details": {}
  }
}
```

## Notas Adicionales

- Asegurate de incluir un ID válido en la solicitud para obtener la información
  sobre un objeto interactivo en específico.