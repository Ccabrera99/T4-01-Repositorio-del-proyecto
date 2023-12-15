# Endpoint: `POST /objetos-interactivos`

Permite añadir un nuevo objeto interactivo a la coleccion de objetos interactivos.

## Ejemplo de Solicitud
```http
POST http://localhost:1337/api/objetos-interactivos
```
```json
{
    "data":{
        "descripcion":"Adquiere objetos de mejora",
        "nombre":"Cofre"
    }
}
```

## Respuesta Exitosa (Código 200 OK)
```json
{
    "data": {
        "id": 2,
        "attributes": {
            "createdAt": "2023-12-15T08:06:23.424Z",
            "updatedAt": "2023-12-15T08:06:23.424Z",
            "publishedAt": "2023-12-15T08:06:23.423Z",
            "descripcion": "Adquiere objetos de mejora",
            "nombre": "Cofre"
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

- Asegurate de incluir los parametros adecuados para agregar un objeto interactivo.
