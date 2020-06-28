FROM node:lts-alpine
RUN npm install -g @angular/cli
WORKDIR /app
RUN ng new angulardocker

# Angular # - Docker
# Ejecuta un nuevo proyecto de angular en docker en modo desarrollo.

## Comando a seguir:

# - docker build -t angular ./proyecto_angular/.
# - docker run -itd -v ${PWD}:/app --name angularWeb angular
# - docker exec -it angularWeb ng new proyectName --directory=.
# - sudo chown -R $USER:$(id -gn $USER) ./*
# - docker rm -f angularWeb
# - docker-compose up
# - docker-compose exec web comandoToRun
# - Example: -
# - docker-compose exec web ng generate component xyz // Esto crea un componente en el proyecto
