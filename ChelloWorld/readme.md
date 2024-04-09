Resolucion del tp0:

// Instrucciones para la instalacion y configuracion de nuestro IDE y el compilador

Primero instalaremos visual studio code (https://code.visualstudio.com) que sera nuestro editor de texto durante el resto de la cursada

Para configurar correctamente el IDE, una vez abierto: Iremos en la parte superior a Windows -> General -> WorkSpace |---> Text File encording -> Other -> |---> Next text file line delimiter -> Other -> Unix

Luego nos desplazamos a C/C++ -> Build |-> Enviroment -> ADD ----> Y comolocaremos como name: "Path" y value: "C:\MinGW\bin" |-> New C/C++ proyect wizard -> desabilitaremos la opcion que dice "Show proyect types (...)" y seleccionaremos en Toolchain "MinGW GCC"

Y ya tendremos listo y configurado nuestro IDE y nuestro compilador para su correcto uso

// Resolucion del archivo hello.c

Ya configurado el IDE, emepezaremos a realizar el archivo de hello.c
En este archivo lo unico que haremos sera mostrar por pantalla el texto "Hola, mundo!", para eso primero pondremos la biblioteca stdio.h para poder utilizar la funciones de entrada y salida. Luego escribiremos la funcion printf proporcionada por la biblioteca anterior y saldra por consola el texto que escribiremos "Hola, Mundo!" y por ultimo la linea de codico "return 0" al retornara 0 terminar de ejecutar la funcion principal
