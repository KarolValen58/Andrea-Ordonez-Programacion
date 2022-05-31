# Programa en c++ de Andrea Ordonez
![82427416-código-de-programación-de-fondo-abstracto-de-la-tecnología-de-software-de-software-y-escribir-la-com](https://user-images.githubusercontent.com/101119779/171087545-6cd271c1-98b3-4d04-a222-95cccf5f5660.jpg)

# Datos de la Creadora
### Nombres de la Creador:
Andrea Carolina Ordóñez Valencia
#### Correo Electronico: 
andrea.ordonez.valencia@utelvt.edu.ec
#### Actividad B1 video explicativo
https://www.youtube.com/watch?v=f7VARsCfIgE&t=197s

##  PROGRAMAS
### 1. Suma de varios numeros
### 2. Comparacion de dos numeros
### 3. Contador de Monedas
### 4. Punto de Venta
### 5. La Edad de una persona

# DESCRIPCION DE CADA PROGRAMA
### 1. Suma 
El programa permite obtener el valor de los numeros sumados, evaluando la cantidad de numeros registrados y el valor de cada cantidad.
### FUNCIONALIDAD
#### ¿Como funciona?

##### -Primer paso declarar variables, puede ser en numeros o letras.

int AB_x=0, AB_p;

float AB_v, AB_t=0;

##### -Luego mostrar en pantalla utilizando el comando "cout" para mencionar acualquier tipo de comentario.

cout<<"Escriba la cantidad de los producto a sumar: "<<endl;

##### -Luego introducir la variable utilizando el comando de "cin".

cin>> AB_p;

##### -En este caso se esa utilizando una estructura repetitiva la cual ejecutar el bloque de instrucciones y, después, se evalúa la condición. En el caso de que ésta sea verdadera, se vuelve a ejecutar el bloque de instrucciones. Y así sucesivamente, hasta que, la condición sea falsa.

do {
		
    cout<<"Escriba el valor del numero: "<<endl;
		
    cin>>AB_v;
		
    AB_x=AB_c+1; 
		
    AB_t=AB_t+AB_x;
	
  } while (AB_x<AB_p);  
### SALIDA
##### -El programa mostrará su resultado obtenido.

cout<<"La porcion de numeros digitados es: "<<AB_p<<endl;

cout<<"El valor obtenido de la suma es: "<<AB_t<<endl;

### 2. COMPARA "<" ">"
Este programa nos permite evaluar dos cantidades o valores y asi mismo llegar a una conclusión de que cantidad es mayor y cual menor o, si ambos valores son iguales.
### FUNCIONALIDAS
##### -Declarar variables

float  AB_C, LJ_D;

##### -Se mostrara en pantalla el comentario y ingresar las variables con el comando "cin".

cout<<"Escribir el valor: "<<endl;
  
cin>>AB_C;
  
cout<<"Escribir el valor: "<<endl;
  
cin>>AB_D;

##### -En este caso se utilizara una estructura de tipo selectiva doble la cual permite definir una condición que se debe cumplir y de acuerdo a su cumplimiento o no tomar una acción correspondiente. 

if (AB_C==AB_D) {

	cout<<"Los dos valores son iguales"<<endl;
	}
	else if (AB_C>AB_D){
		cout<<"Valor "<<AB_C<<" es mayor que "<<AB_D<<endl;
	}
	else{
		cout<<"Valor "<<AB_D<<" es mayor que  "<<AB_C<<endl; 
	} 
  
### SALIDA
##### -Mostrando los resultados obtenidos del programa
cout<<"Los dos valores son iguales"<<endl;
	
cout<<"El valor "<<AB_C<<" es mayor que "<<AB_D<<endl;
	
cout<<"El valor "<<AB_D<<" es mayor que  "<<AB_C<<endl; 
	
### 3. CONTADOR DE MONEDAS
Este programa permite que podamos contar o obtener la suma total de las monedas ingresadas, el numero de monedas que fueron digitadas, el valor de las monedas y cuantas monedas de (0.10, 0.25).

### FUNCIONALIDAD
#### ¿Como funciona?
##### -Declaramos variables
int  AB_n, AB_k= 0 , AB_k1= 0 , AB_k2= 0 ;

float  AB_x, AB_i= 0 , AB_i1= 0 , AB_i2= 0 ;

##### -Ingresamos un comentario y introducimos la variable.
  
cout<< "Escriba el valor de monedas a contar :" <<endl;

cin>>AB_n;
