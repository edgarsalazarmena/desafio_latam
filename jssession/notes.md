naming conventions
	reglas que usamos para nombrar variables, necesarias para que haya un mejor entendimiento 2 tipos=camel case y first name

nombrar funciones 
	empieza con minuscula y despues mayuscula

clases y modulos 
	empieza con mayuscula

formas de incluir javasc
	inline, un archivo externo

alert 
	manda un mensaje un numero o una alerta

variables
	una manera o un espacio para guardad un dato ej. /var/ age = 5;

tipos de variables
	Boolean
		=falso o verdadero
	string
		=letra, cadenas de caracteres, "" ''
	number
		=numeros
	undefined
		=no se a dado un valor, lo definiras despues
	null
		=no tiene nada

cada que hagamos una variable la subimos la consola


	operadores logicos
		tomad decisiones

	var age = 5;
	console.log(age);

	var isVerified = true;
	console.log(isVerified);

	var address = "Reims #223";
	console.log(addres);

	var age = 19;
	console.log(age);

	var price = 10.99;
	console.log(price);

	var name;
	console.log(name);

	var nullValue = null;
	console.log(nullValue);

var speed = 10.01;
var age = 10;
var firstName = "Edgar";

	console.log(speed > 11 && age < 11);
	console.log(speed > 9 || age <12);
	console.log(speed == age);
	console.log(speed === age);
	console.log(speed !== age);
	console.log(! (age > 18));
	type of

var n1 = 10;
var n2 = 25.60;

console.log(n1 + n2);
console.log(n1 - n2);
console.log(n1 * n1);

console.log((n1 + n2) * n1 / (n1 % n2);

var age = prompt ("your age?");
var gender = "female";
var isMom = false;
var legalAgeFemale = age >= 18 && gender == 'female'

	if (isMom){
	    alert("Entra gratis por 10 de mayo")
	}
	if (legalAgeFemale) { 
	    alert("Entra gratis!!!");
	} else {
	    alert("Pagale chavo");
	}

var password = 'password';
var userPassword = '';

do {
    userPassword = prompt("Dime el password");
}while(userPassword != password);

alert("Estas logueado!");


var password = 'password';
var userPassword = '';

var pregunta = 'perro';
var userPregunta = prompt('Como se llama: ');

while(userPregunta != pregunta){
        userPassword = prompt('como se llama tu perro:')
    

	while(userPassword != password) {
    	userPassword = prompt('Ingresa tu password: ');
    }
    
    
};


alert('Bienvenido');

var password = 'password'
var userPassword = '';
for(var i = 0; i<10; i++){
    userPassword = prompt("cual es tu password?" + i);
    if (userPassword == password)
    {
        alert("bienvenido")
        break
    }
    else
    {
        alert("Internalo de nuevo");
    }
} 

var upTo = prompt("hasta que numero quieres sumar:");
var sum = 0;

for(var i=0; i < upTo; i ++){
    sum = sum + i;
     
}

alert(sum);

---------------------------------------------

var upDown = parseInt(prompt("hasta que numero quieres sumar:");
var sum = 0;

for(var i=upDown; i >= upDown; i --){
    sum = sum + i;
     
}

alert(sum); 

var upTo = prompt("hasta que numero quieres sumar:");
var sum = 0;
                      
var i = 1;

while(i <= upTo){
    sum = sum + i;
    i++;
}


alert(sum);  

----------------------------------------------
float
	numero decimal
int
	numero entero

----------------------------------------------
operadores aritmenticos
	+ - % * ++ --

condicionales
	if, else, else if
	si, si no, si no si
	var



piedra papel o tijera
---------------------------------------------

while y do while
for

parseint
	evita errores de numeros

usar break para romper

var number = parseInt(prompt("Digita un numero"));
var primo = true;


if(number <= 1){
    primo = false;
    console.log("No es primo");
}
else {
    for( i = 2; i < number; i++){
        if( number % i == 0){
            primo = false;
            console.log("No es numero primo!!");
            break;
            
        } 
    }
}



 generar numeros primos
 poner cantidad de numeros primos que quieres y te los dice
---------------------------------------------
estructura de datos java
	soporte de datos, la base
		arreglos, hash y mas

arreglos
	estructura de datos ordenada, contiene elementos
metodos
	se ejecutan sobre algo
	lenght/numero de elementos
	push/agregar elemento al final
	pop/saca ultimo elemento de la lista
	shift/quita primer elemento
	unshift/
	concat/
array
	lista de datos, cualquiera,
	guardar variables, guardar semanas, meses, agrupasr elementos

//length push pop shift unshift concat
var userList = ['edgar', 'juan']
var numberList = [1, 2, 3, 4]


userList.push("juanito");
userList.pop("juanito");

console.log(userList);

numberList.shift(10);
numberList.shift();

numberList.unshift(10);
console.log(numberList);

shift, unshift, order, concat, join

.map
The map() method creates a new array with the results of calling a provided function on every element in this array.

hashes
------------------



