## TP0 - "Hello, world!" en c

// Instrucciones para la instalacion y configuracion de nuestro IDE y el compilador

Primero instalaremos visual studio code (https://code.visualstudio.com) que sera nuestro editor de texto durante el resto de la cursada

Luego de instalar el editor de texto tendremos que instalar el compilar de c, en este caso usaremos gcc y e instalaremos a partir de cywing (https://cygwin.com)

Iremos a "Editar variables de entorno del sistema" -> "Variables de entorno" -> "Variables del sistema" -> "PATH" y añadimos la direccion de "cywing\bin" 

Paralelamente tendremos que instalar git (https://git-scm.com) asi podremos crear una conexion entre github y nuestra PC. Una vez instalado git procederemos a crear una key SSH siguiendo los pasos de (https://docs.github.com/es/authentication/connecting-to-github-with-ssh). Ya conectados la pc con github crearemos un repositorio para la materia, que tendra una clave SSh que la utilizaremos desde la terminal para clonar dicho repositorio con "git clone <clave SSH>"

Una vez que tengamos el repositorio creado, nuestro entorno de desarrollo y nuestro comilador es hora de vincular nuestro repositorio con el compilador dentro de nuestra entorno de desarrollo para compilar correctamente los programas. Ahi estableceremos la carpeta ".vscode" con dos archivos tasks.json y launch.json. El primero de ellos nos permita automatizar tareas, para el espectro que utilizaremos en esta materia procedi a crear tres tares: compilacion, ejecucion y otra que grabara en un archivo output.txt la salida del programa .exe. Y en el launch.json esta configura para utilizar el "run and debugger" de vscode. Para utilizar el primero que realiza las tres tareas iremos a la parte de arriba "Terminal -> Run task(en el caso que queramos utilizar alguna de las funciones especificas) || Run build tasks(Utiliza las tres funciones al mismo tiempo) y para el segundo "Start debuggin $$ Run"

Y ya tendremos listo y configurado nuestro IDE y nuestra conexion con github 

// Resolucion del archivo hello.c

Ya configurado el IDE, emepezaremos a realizar el archivo de hello.c
En este archivo lo unico que haremos sera mostrar por pantalla el texto "Hola, mundo!", para eso primero pondremos la biblioteca stdio.h para poder utilizar las declaraciones funciones basicas de c. Luego en la funcion int main() (determina que es un programa ejecutable) escribiremos la funcion printf proporcionada por la biblioteca anterior y saldra por consola el texto que escribiremos "Hola, Mundo!" y por ultimo la linea de codigo "return 0" al retornara 0 terminar de ejecutar la funcion principal

Para finalizar tendremos escribi por consola "git add ." y "git commit -m 'nombre del utilimo commit'" y para subirlo en github finalizamos con un git push

Ademas de todo esto adjunto una foto corriendo el codigo por consola en vez de utilizar el vscode
