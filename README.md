# Backend desde cero

#### Actualmente la arquitectura cliente-servidor es de las más usadas y de las que más trabajo ofrece a nivel mundial, teniendo eso en cuenta, me propuse a crear este curso para aprender el apartado de "servidor" desde cero. Espero les sea de utilidad y les sea de ayuda tanto para los que solo quieren aprender por hobbie, como a los que pretenden comenzar una carrera profesional en el sector de la programación.


### Requisitos previos

* `JavaScript`: Es necesario tener ciertas nociones en este lenguaje de programación, pero no será necesario un manejo muy elevado del mismo, ya que se explicarán a detalle cada uno de los aspectos que se verán a lo largo del curso.

* `HTML y CSS` Si bien el objetivo de este curso es el de aprender sobre la parte de servidores, a largo del mismo se verán ciertas formas de interactuar con las tecnologías mensionadas por lo que se espera tener ciertas nociones básicas de las mismas.

* `Café`, `Snacks` y múchas ganas de aprender!! 

---
# Indice: 
### ¿Qué es nodeJS?
* [node](https://nodejs.org/en/) y [npm](https://www.npmjs.com) (package.json, librerías y tipos de librerías)
* Scripts de package.json
* Versionamiento de las librerías
* ¿CommonJS o ESModules?

### Trabajemos cómodos
* Atájos de teclado básicos
* Configuración y extensiones de [vscode](https://code.visualstudio.com)

### Nuestro primer CLI
* ¿Qué es un `CLI`?
* ¿Qué podemos hacer con un `CLI`?
* Conocemos [inquirer](https://www.npmjs.com/package/inquirer) y [commander](https://www.npmjs.com/package/commander)
* Creamos nuestro primer `CLI`
* Subimos nuestro proyecto a npm

### El framework de Express
* ¿Qué es [express](https://expressjs.com/es/)?
* Rutas básicas
* Verbos HTTP
* Diversificación de rutas
* Controladores
* Códigos de estado
* Middlewares
* No reinventemos la rueda
* Servicios reutilizables

### No seamos sucios
* ¿Qué es un linter?
* ¿Cuál debería usar?
* Un poco de orden con [ESLint](https://eslint.org)

### Persistencia de datos
* Conexión a mongodb (con [mongoose](https://mongoosejs.com))
* Configuración de variables de entorno
* Modelos y esquemas de mongoose
* Rutas básicas con uso de bases de datos
* Relaciones entre modelos
* Triggers de los modelos en mongoose

### Validaciones de datos en las rutas
* Ejemplos con [express-validator](https://express-validator.github.io/docs/)
* Ejemplos con [zod](https://zod.dev)

### Loggers
* ¿Qué eso y para que sirven?
* Creamos nuestro propio logger
* ¿Cómo usar el logger manager de morgan?

### Session de usuarios
* [JWT](https://jwt.io) (Json Web Tokens)
* Como generar nuestro token
* Como validar nuestro token
* Rutas de autentificación
* Rutas privadas
* [passport](http://www.passportjs.org) + [passport-jwt](http://www.passportjs.org/packages/passport-jwt/) para validar las rutas privadas
* Verificar el token y uso de la blacklist

### Hablemos sobre seguridad
* ¿Qué tan importante es?
* No dar información de más
* Limitar las peticiones
* Banneo de IPs

### Versionamiento del código
* [Git](https://git-scm.com) + [Github](https://github.com)
* ¿Cómo hacer un commit en condiciones?
* Manejo de distintas ramas

### Pruebas automatizadas
* Introducción al testing
* [Jest](https://jestjs.io)
* Jest + [Supertest](https://www.npmjs.com/package/supertest)

### Vayámos más allá
* ¿Qué es [TypeScript](https://www.typescriptlang.org)?
* Curso básico sobre TypeScript
* ¿Debémos usar JavaScript o TypeScript?
* Pasamos el proyecto a TypeScript

### Proyecto a producción
* Hablemos sobre deploy
* ¿Por qué NO usar Heroku?
* Alternativas a Heroku
* Deploy del proyecto

### ¿Clean [Architecture](https://clean-architecture-python.readthedocs.io/en/latest/fundamentos/index.html#solid)?
* Código limpio
* Código escalable
* Ventajas y Desventajas
* Ejemplos

### ¿Principios SOLID?
* ¿Qué es [SOLID](https://profile.es/blog/principios-solid-desarrollo-software-calidad/) y en que me beneficia?
* ¿Valen la pena?
* Ejemplos

### El framework de NestJS
* ¿Qué es [NestJS](https://nestjs.com)?
* Conozcamos a [@nestjs/cli](https://www.npmjs.com/package/@nestjs/cli)
* Hacemos nuestra primer api rest con NestJS
* Validamos los datos del body
* Utilizamos mongoose con NestJS
* Hacemos inicio de sesión con JWT