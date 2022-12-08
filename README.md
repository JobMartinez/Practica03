# Practica03
Escribir un programa en NodeJS en el cual escriba una frase de al menos 12 palabras y terminando cada palabra debe contener una coma ",".


/*
19070686 - JOB MARTINEZ CARDENAS - Lenguajes Y Automatas II
PRACTICA 3
*/

var cadena = "Hola,mucho,gusto,bienvenido,al,Instituto,Tecnologico,de,San,Luis,Potosi,Capital";
const espacio= ' ';
var cadenaremp = cadena.replaceAll(",", " ");

console.log(cadenaremp);
console.log("Tamano cadena: ",cadenaremp.length);
