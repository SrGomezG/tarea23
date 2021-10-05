# TAREA #23

## PARTICIPANTES
1. Santiago Gomez Garcia .........
2. Sebastián Ladino Cano .........

## Ejercicio #1
var nombre = prompt("Ingrese nombre");
console.log("Ahora estás en la matrix " + nombre);

## Ejercicio #2
var a = prompt("Primer Número:");
var b = prompt("Segundo Número:");
c=parseInt(a)+parseInt(b);
console.log("El resultado de la suma es", c);

## Ejercicio #3
var n1=prompt("Ingrese un número:");
var n2=prompt("Ingrese otro número:");
suma=parseInt(n1)+parseInt(n2);
console.log("Suman:", suma);
var n3=prompt("Ingrese un nuevo número:");
console.log("Multiplicación de la suma por el último número:", suma* parseInt(n3));

## Ejercicio #4
var kilometros=prompt("Kilómetros recorridos:");
var litros=prompt("Litros de combustible gastados:");
console.log("El consumo por kilómetro es de: " + parseFloat(kilometros)/parseFloat(litros));

## Ejercicio #5
var Fahrenheit=prompt("Ingresá una temperatura expresada en Fahrenheit:");
console.log((5/9) * (parseFloat(Fahrenheit)-32));

(parseFloat(n1)+parseFloat(2)+parseFloat(n3))/3);
## Ejercicio #6
var n1=prompt("Primer número: ");
var n2=prompt("Segundo número: ");
var n3=prompt("Tercer número: ");
console.log("El promedio de los tres es ", (parseFloat(n1)+parseFloat(2)+parseFloat(n3))/3);

## Ejercicio #7
var numero=prompt("Ingrese un número:");
console.log("Descontando el 15% queda:", parseInt(numero)-(parseInt(numero)*15)/100);

## Ejercicio #8
var palabra1=prompt("Primera palabra:");
var palabra2=prompt("Segunda palabra:");
frase=palabra1+" "+palabra2;
console.log(frase);

## Ejercicio #9
var cadena=prompt("Ingrese un texto:");
console.log("El carácter en primer lugar es:", cadena[0]);
console.log("Ingrese un número positivo menor a", cadena.length);
var indice=parseInt(prompt());
console.log("El carácter en esa posición es:", cadena[indice]);

## Ejercicio #10
var shows=parseInt(prompt("Shows vistos en el último año:"));
console.log(shows>3);

## Ejercicio #11
var fecha=prompt("Fecha en formato DDMMAAAA:");
var año=parseInt(fecha)%10000;
var dia=parseInt(fecha)/1000000;
var mes=parseInt(fecha)/10000%100;
console.log(dia,"/",mes,"/",año);

## Ejercicio #12
var numero=prompt("Número entero:");
console.log(parseInt(numero)%2 == 0);

## Ejercicio #13
var edad=prompt("Tu edad:");
var articulos=prompt("Artículos comprados:");
console.log((parseInt(edad)>18) && (parseInt(articulos)>1));

## Ejercicio #14
var cadena=prompt("Ingresá una frase:");
longitud=cadena.length;
console.log(parseInt(longitud)%2 == 0);

## Ejercicio #15
var palabra1=prompt("Una palabra:");
var palabra2=prompt("Otra palabra:");
console.log(parseInt(palabra1)<parseInt(palabra2));

## Ejercicio #16
var nombre1=prompt("Tu nombre:");
var nombre2=prompt("Otro nombre:");
var posicionFinalN1=nombre1.lenght-1;
var posicionFinalN2=nombre2.lenght-1;
console.log((nombre1[0] == nombre2[0]) || (nombre1[posicionFinalN1] == nombre2[posicionFinalN2]));

## Ejercicio #17
var numero=prompt("Número:");
if (parseInt(numero)<0)
    numero=numero*-1;
console.log("Valor absoluto:", numero);

## Ejercicio #18
var numero1=prompt("Un número:");
var numero2=prompt("Otro número distinto:");
if (parseInt(numero1)>parseInt(numero2))
    console.log(numero1, "es mayor");
else
    console.log(numero2, "es mayor");

## Ejercicio #19
var letra=prompt("Letra:");
if (letra.lenght>1)
    console.log("Debe ser sólo una letra");
else
    if (letra=="a" || letra=="e" || letra=="i" || letra=="o" || letra=="u")
        console.log("Es vocal");

## Ejercicio #20
var n1=prompt("Primer número:");
var n2=prompt("Segundo número:");
var n3=prompt("Tercer número:");
if (n1<n2)
    if (n1<n3)
        console.log("Menor:", n1);
    else
    console.log("Menor:", n2);
else
    if (n2<n3)
    console.log("Menor:", n3);
    else
    console.log("Menor:", n4);

