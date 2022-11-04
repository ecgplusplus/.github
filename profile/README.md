# Bienvenid@ a ECG++
## Plataforma de aprendizaje de electrocardiogramas

![Logo](/images/logo_ecg.png)

## Proyectos

* `ecgplusplus-terraform-iaac`: Infraestructura como código usando Terraform
* `ecgplusplus-users-api`: API REST para aplicacion de usuarios usando NodeJS.
* `ecgplusplus-database`: Migraciones de base de datos usando Prisma
* `ecgplusplus-user-frontend`: Aplicación frontend para usuarios usando Angular.
* `ecgplusplus-cronjobs`: Tareas periódicas usando NodeJS y Serverless Framework.
* `ecgplusplus-landing`: Landing page de la empresa usando Angular.

## Levantando el stack de desarrollo local

1. Clonar el repositorio `ecgplusplus-database` y ejecutar `./run.sh`
2. En el repositorio `ecgplusplus-database` ejecutar `npm run migrate:dev`
3. Clonar el repositorio `ecgplusplus-users-api` y ejecutar `./run.sh`
3. Clonar el repositorio `ecgplusplus-user-frontend` y ejecutar `npm install && npm run start`