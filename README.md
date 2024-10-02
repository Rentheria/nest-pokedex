<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en Desarrollo

1. Clonar el repositorio

2. Ejecutar

   ```
   yarn install
   ```

3. Tener Nest CLI

   ```
   npm i -g @nestjs/cli
   ```

4. Levantar la base de datos

   ```
   docker-compose up -d
   ```

5. Clonar el archivo `.env.template` y renombrar la copia `.env`

6. Llenar las variables de entorno definidas en el `.env`

7. Ejecutar la aplicacion en dev:

   ```
   yarn start:dev
   ```

8. Reconstuir la DB con Seed

   ```
   http://localhost:300/api/v2/seed
   ```

# Stack usado

- MongoDb
- Nest
