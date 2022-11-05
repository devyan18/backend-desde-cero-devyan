# ¿Qué es NodeJS?
Si le hacemos esa pregunta a google nos responde con esto:

> Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto, para la capa del servidor basado en el lenguaje de programación JavaScript, asíncrono, con E/S de datos en una arquitectura orientada a eventos y basado en el motor V8 de Google.

De la anterior cita, por el momento, solo nos interesa la parte en la dice 'multiplataforma' lo cuál significa que nodejs puede ser ejecutado en cualquier tipo de dispositivo, a diferencia del JavaScript del navegador que, valga la redundancia, solo se puede ejecutar en navegadores y no en todos funcionan de la misma forma. Tener en cuenta lo anterior será muy útil para el desarrollo de este curso.

Vayámos directo al grano, tal vez si llegaste a este curso ya tienes una idea de lo que es y para lo que sirve, asi que no voy a darle más vueltas.

Primero que nada tenemos que instalar el runtime de nodejs.

¿Cómo lo hacemos?

Sencillo, podemos buscar nodejs en google y entrar en el enlace que diga [https://nodejs.org/](https://nodejs.org/)

Siempre existen 2 alternativas, la lts o latest que es la última versión totalmente estable del runtime y por otro lado la current es la última versión del mismo pero esta puede llegar a presentar problemas. Aunque para el alcance de este curso les recomiendo instalar la versión latest.

> Ten en cuenta que cada sistema operativo tiene una forma un poco distinta de instalar, la página oficial detalla muy bien los pasos a seguir para la instalación de la misma en los diferentes sistemas operativos por la que no deberías tener complicaciones al momento de instalarlo.

# ¿Qué es NPM?

Decidí poner ambas tecnologías juntas ya que concidero que es importante saber ambas antes de pasar a cualquier otro apartado, NPM o Node Package Manager, como su nombre lo indica, es un manejador de paquetes de node, pero, ¿qué es un paquete y por qué necesitamos un manejador?

Primero contestemos la primer pregunta ¿Qué es un paquete?

> Esta pregunta es fácil de contestar, un paquete, librería o biblioteca, en el contexto de node, son ciertas funcionalidades ya préviamente creadas, las cuales estan a nuestra disposición para nuestro uso de forma gratuita. De las mismas existen 2 tipos, las propias del runtime, también llamadas "librería estandar" o "std" y las librerías de terceros, y es en este punto donde entra NPM.

> NPM es una herramienta que nos permite descargar y manejar de forma fácil las librerías de terceros que descargamos y nos permite tener un seguimiento de los paquetes que se necesitan tener para el correcto funcionamiento de un proyecto.

---

# Comencemos a usar node y npm

Suficiente de teoría, vayamos a la práctica, para poder usar node, luego de aberlo instalado, podemos ingresar a nuestra terminal y escribir lo siguiente

```cmd
node --version
```

Damos enter y nos debería responder algo como esto:

> v18.11.0

No importa si los números no son exactamente iguales, si nos responde mostrandonos la versión significa que tenemos acceso al cli de node.

> Más adelante en el curso profundizaremos en que es un pero solo para aclarar, son las siglas de "Command Line Interface".

Luego de esto podemos repetir el proceso para npm con:

```cmd
npm --version
```

Luego del enter debería respondernos con algo parecido a ésto:

> 8.19.2

Por motivos de prevenir posibles errores, les recomiendo que la versión de tanto NodeJS, como la de NPM sea 16+ y 7+ respectivamente.

> En el caso de nodejs es necesario instalar manualmente o a través de NVM la versión, pero en el caso de npm, podemos escribir el siguiente comando:

```cmd
npm install -g npm@latest
```

Luego de esto, podemos escribir

```cmd
node
```

En la terminal y nos debería responder con algo como esto:

```
Welcome to Node.js v18.11.0.
Type ".help" for more information.
> |
```
Esto es el REPL (Read-Eval-Print-Loop) de Node JS la cuál es una herramienta de cónsola que te permite evaluar declaraciones en JavaScript y ver sus resultados inmediatamente.

Por ejemplo, si hacemos una operación matemática com una suma, nos responderá con el resultado.

```
Welcome to Node.js v18.11.0.
Type ".help" for more information.
> 1+1
2
>
```

Si bien esta herramienta es útil en muchos casos, en este curso no profundizaremos tanto en ella, pero es útil saber que existe y como se llama por si quieren buscar más información en un futuro.

