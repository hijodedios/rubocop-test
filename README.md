# Rubocop Test

## Descripción

Este es un proyecto de ejemplo para aprender a utilizar Rubocop en un proyecto de Ruby on Rails.

## Requerimientos

- Ruby 2.6.6
- Rails 6.0.3.2
- PostgreSQL
- Docker

## Ejecución del contenedor con la  base de datos Docker Compose

Para arrancar la base de datos utilizando Docker Compose, sigue los siguientes pasos:

1. Asegúrate de tener Docker Compose instalado en tu máquina.
2. Abre una terminal y navega hasta el directorio del proyecto.
3. Ejecuta el siguiente comando para iniciar los servicios de Docker Compose:

docker-compose up

4. Para mas detalles de la base de datos ver el archivo docker-compose.yml

## Instalación

1. Clonar este repositorio: `git clone https://github.com/hijodedios/rubocop-test.git`
2. Instalar las dependencias: `bundle install`
3. Configurar la base de datos en `config/database.yml`
4. Crear la base de datos: `rails db:create`
5. Correr las migraciones: `rails db:migrate`

## Uso

Para iniciar la aplicación, ejecutar el comando:

rails s

## Ejecución de Rubocop

Para correr Rubocop en el proyecto, ejecutar el siguiente comando en la terminal:

rubocop


## Contribuciones

Si quieres contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio
2. Crea una rama para tu feature: `git checkout -b mi-feature`
3. Haz los cambios necesarios en tu rama
4. Haz commit y push de los cambios: `git commit -m "mi mensaje de commit" && git push origin mi-feature`
5. Abre un Pull Request en Github y describe los cambios que hiciste.

## Licencia

Este proyecto está bajo la licencia MIT.

