# Endpoint: `GET /especies-y-habitats/{id}`

Permite obtener información detallada sobre una especie y habitat específico mediante su identificador único.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único de la especie y habitat que se desea recuperar.

## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/especies-y-habitats/1
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 1,
        "attributes": {
            "createdAt": "2023-12-15T07:21:19.624Z",
            "updatedAt": "2023-12-15T07:26:25.554Z",
            "publishedAt": "2023-12-15T07:21:23.000Z",
            "especie": "Merodeador"
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
  sobre una especie y habitat en específico.