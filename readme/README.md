# Documentación de la API RESTful 

Bienvenido a la documentación de la API. A continuación, se presenta una lista
de endpoints disponibles con enlaces a sus respectivas documentaciones detalladas
"Explora Natura" será un videojuego educativo de plataformas en 2D, diseñado 
para ofrecer una experiencia interactiva y enriquecedora centrada en el descubrimiento y aprendizaje sobre la naturaleza.

## Descripción General de Endpoints 

| Recurso                    | Descripción |
| -------------------------- | ----------- |
| [`GET /especies-y-habitats`](./endpoints/get-especies-y-habitats.md)               | Recupera la lista de todos las especies y habitats disponibles. |
| [`GET /especies-y-habitats/{id}`](./endpoints/get-especies-y-habitats-id.md)          | Obtiene información detallada sobre una especie y habitat específico. |
| [`POST /especies-y-habitats`](./endpoints/post-especies-y-habitats.md)             | Agrega una nueva especies y habitats a la coleccion existente.
| [`DELETE /especies-y-habitats//{id}`](./endpoints/delete-especies-y-habitats.md)             | Borrado total de un usuario existente mediante su identificador unico.
| [`GET /jugadores`](./endpoints/get-jugadores.md)              | Recupera la lista de todos los jugadores disponibles. |
| [`GET /jugadores/{id}`](./endpoints/get-jugadores-id.md) | Obtiene la lista de un jugador específico. |
| [`POST /jugadores`](./endpoints/post-jugadores.md)             | Agrega un nuevo jugador a la coleccion existente.
| [`DELETE /jugadores/{id}`](./endpoints/delete-jugadores.md)             | Borrado total de un jugador existente mediante su identificador unico.
| [`GET /guias`](./endpoints/get-guias.md)             | Recupera la lista de todos las guias disponibles. |
| [`GET /guias/{id}`](./endpoints/get-guias-id.md)        | Obtiene información detallada sobre una guia específica. |
| [`POST /guias`](./endpoints/post-guias.md)             | Agrega una nueva guia a la coleccion existente.
| [`DELETE /guias/{id}`](./endpoints/delete-guias.md)             | Borrado total de una guia existente mediante su identificador unico.
| [`GET /objetos interactivos`](./endpoints/get-objetos-interactivos.md)             | Recupera la lista de todos los objetos interactivos disponibles. |
| [`GET /objetos interactivos/{id}`](./endpoints/get-objetos-interactivos-id.md)        | Obtiene información detallada sobre un objeto interactivo específica. |
| [`POST /objetos interactivos`](./endpoints/post-objetos-interactivos.md)             | Agrega un objeto interactivo a la coleccion existente.
| [`DELETE /objetos interactivos/{id}`](./endpoints/delete-objetos-interactivos.md)             | Borrado total de una actividad existente mediante su identificador unico.