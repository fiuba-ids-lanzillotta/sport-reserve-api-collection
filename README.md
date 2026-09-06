# sport-reserve-api-collection

Colección de peticiones de [Bruno](https://www.usebruno.com/) para consumir la **Sport Reserve API**.

## Estructura

- `Deportes`
- `Canchas`
- `Socios`
- `Reservas`
- `Bloqueos` (extensión)
- `Recurrentes` (extensión)

## Entorno

Usá el entorno `Local` configurado con:

- `protocol`: `http`
- `host`: `localhost:5000`
- `base_url`: `/sport_reserve_api`

Si el servidor corre en otro puerto, modificalo en `environments/Local.bru`.

## Requisitos

- Bruno instalado.
- API levantada (rama `feature/extended_implementation` para todos los endpoints, o `feature/db_implementation` / `main` para endpoints base).

## Uso

1. Abrí la colección en Bruno.
2. Seleccioná el entorno `Local`.
3. Ejecutá las peticiones en el orden deseado.
