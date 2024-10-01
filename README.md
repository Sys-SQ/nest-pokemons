<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

# Ejecutar en desarrollo
0. Compila en modo de desarrollador
```
npm run start:dev
```
1. Clonar el repositorio

2. Ejecutar
```
npm install 
```

3. Tener Nest CLI instalado
```
npm i -g nestjs/cli
```

4. Levantar la baser de datos
```
docker-compose up -d
```

5. Clonar el archivo __.env.template__ y renombrar la copia a __.env__
```
http://localhost:3000/api/v2/seed
```

6. Llenar las varibales de entorno definidas en el ```.env```

7. Ejecutar la aplicación en dev:
```
npm run start:dev
```

8. Recosntruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed
```

## Stack usado 
* MongoDB
* Nest
