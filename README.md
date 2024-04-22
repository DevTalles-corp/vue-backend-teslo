# Nest - TesloShop Backend

## Development
1. Tener corriendo el servicio de Docker (Docker Desktop o Docker Daemon)
2. Clonar el archivo __.env.template__ y renombrar la copia a __.env__
3. Levantar los servicios con el comando
```
docker compose up -d
```
4. Llenar la base de datos con data temporal:

    http://localhost:3000/api/seed

5. Documentación de los endpoints disponibles:

    http://localhost:3000/api


## Alternativa:

1. Descargar todo el backend y seguir los pasos del README del proyecto de NestJs
[Backend completo](https://github.com/Klerith/nest-teslo-shop/tree/complete-backend)

2. Siempre será necesario Docker, pero sólo para la base de datos, la cual se puede cambiar por un servicio como [NeonTech](https://neon.tech/)


# Extra
Si desean saber más sobre docker y cómo se construyó esta imagen, esto es parte de mi curso de Nest y Docker:

[Cursos sobre Docker](https://fernando-herrera.com/#/search/docker)

[Imagen en DockerHub](https://hub.docker.com/repository/docker/klerith/flutter-backend-teslo-shop/general)
