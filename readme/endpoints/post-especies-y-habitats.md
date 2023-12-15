# Endpoint: `POST /especies-y-habitats`

Permite añadir una nueva especie y habitat a la coleccion de especies y habitats.

## Ejemplo de Solicitud
```http
POST http://localhost:1337/api/especies-y-habitats
```
```json
{
    "data":{
        "especie":"Vigilante"
    }
}
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
- Código 400 Bad Request:

```json
{
    "data": null,
    "error": {
        "status": 400,
        "name": "ValidationError",
        "message": "Missing \"data\" payload in the request body",
        "details": {}
    }
}
```

## Notas Adicionales

- Asegurate de incluir los parametros adecuados para agregar una especie y  habitat.
