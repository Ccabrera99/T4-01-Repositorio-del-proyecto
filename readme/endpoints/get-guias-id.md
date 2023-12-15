# Endpoint: `GET /guias/{id}`

Permite obtener información detallada sobre una guia específico mediante su identificador único.

## Parámetros de URL
- `{id}` (obligatorio): Identificador único de la guia que se desea recuperar.

## Ejemplo de Solicitud
```http
GET http://localhost:1337/api/guias/1
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 1,
        "attributes": {
            "Informacion": "Subir nivel",
            "createdAt": "2023-12-15T07:21:33.526Z",
            "updatedAt": "2023-12-15T07:21:40.675Z",
            "publishedAt": "2023-12-15T07:21:40.673Z"
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
  sobre una guia en específico.