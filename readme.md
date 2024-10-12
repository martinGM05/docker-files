# Proyecto de Bases de Datos con Docker

Este proyecto tiene la intención de facilitar la creación y gestión de bases de datos utilizando Docker. Contiene configuraciones para MongoDB y PostgreSQL.

## Estructura del Proyecto

## Requisitos

- Docker
- Docker Compose

## Configuración y Uso

### MongoDB

1. Navega al directorio `mongo`:
    ```sh
    cd mongo
    ```
2. Levanta el contenedor de MongoDB:
    ```sh
    docker-compose up -d
    ```
3. MongoDB estará disponible en `localhost:27017`.

### PostgreSQL

1. Navega al directorio `postgress`:
    ```sh
    cd postgress
    ```
2. Levanta el contenedor de PostgreSQL:
    ```sh
    docker-compose up -d
    ```
3. PostgreSQL estará disponible en `localhost:5432`.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que desees realizar.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.