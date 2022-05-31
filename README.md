# Programa en c++ de Andrea Ordonez
![82427416-código-de-programación-de-fondo-abstracto-de-la-tecnología-de-software-de-software-y-escribir-la-com](https://user-images.githubusercontent.com/101119779/171087545-6cd271c1-98b3-4d04-a222-95cccf5f5660.jpg)

# Datos de la Creadora
### Nombres y Apellidos:
Andrea Carolina Ordóñez Valencia
#### Correo Electronico: 
andrea.ordonez.valencia@utelvt.edu.ec
#### Actividad B1 video explicativo
https://www.youtube.com/watch?v=f7VARsCfIgE&t=197s


##  PROGRAMAS
### 1) Suma de varios numeros
### 2) Comparacion de dos numeros
### 3) Contador de Monedas
### 4) Punto de Venta
### 5) La Edad 


# DESCRIPCION DE CADA PROGRAMA
### 1) Suma 
El programa permite obtener el valor de los numeros sumados, evaluando la cantidad de numeros registrados y el valor de cada cantidad.

### FUNCIONALIDAD

##### Primer paso declarar variables, puede ser en numeros o letras.

int AB_x=0, AB_p;

float AB_v, AB_t=0;

##### Luego mostrar en pantalla utilizando el comando "cout" para mencionar acualquier tipo de comentario.

cout<<"Escriba la cantidad de los producto a sumar: "<<endl;

##### Luego introducir la variable utilizando el comando de "cin".

cin>> AB_p;

##### En este caso se esa utilizando una estructura repetitiva la cual ejecutar el bloque de instrucciones y, después, se evalúa la condición. En el caso de que ésta sea verdadera, se vuelve a ejecutar el bloque de instrucciones. Y así sucesivamente, hasta que, la condición sea falsa.

do {
		
    cout<<"Escriba el valor del numero: "<<endl;
		
    cin>>AB_v;
		
    AB_x=AB_c+1; 
		
    AB_t=AB_t+AB_x;
	
  } while (AB_x<AB_p);  
### SALIDA
##### El programa mostrará su resultado obtenido.

cout<<"La porcion de numeros digitados es: "<<AB_p<<endl;

cout<<"El valor obtenido de la suma es: "<<AB_t<<endl;

### 2) COMPARA "<" ">"
El programa permitira que podamos condicionar o evaluar que cantidad es mayor ">" menor "<" o si las dos terminan siendo iguales

### FUNCIONALIDAS

##### Declarar variables

float  AB_C, AB_D;

##### Luego mostrar en pantalla utilizando el comando "cin" e ingrensando la variable.

cout<<"Escribir el valor: "<<endl;
  
cin>>AB_C;
  
cout<<"Escribir el valor: "<<endl;
  
cin>>AB_D;

##### En esta estructura de tipo selectiva doble permitira definir la condición que se debe cumplir o no tomar una acción correspondiente. 

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
##### Mostrar resultados
cout<<"Los dos valores son iguales"<<endl;
	
cout<<"El valor "<<AB_C<<" es mayor que "<<AB_D<<endl;
	
cout<<"El valor "<<AB_D<<" es mayor que  "<<AB_C<<endl; 

	
### 3) CONTADOR DE MONEDAS
El programa permitira llevar la cuenta o mostrarnos en pantalla la suma total de todas las monedas, el valor  exacto de cada moneda y cuántas monedas de (0.10, 0.25) fueron digitadas.

### FUNCIONALIDAD

##### Declarar variables
int  AB_n, AB_k= 0 , AB_k1= 0 , AB_k2= 0 ;

float  AB_x, AB_i= 0 , AB_i1= 0 , AB_i2= 0 ;

##### Ingresar el comentario e ingresar la variable.
  
cout<< "Escriba el valor de monedas a contar :" <<endl;

cin>>AB_n;

##### Utilizamos una estructura repetitiva como ya habiamos mencionado anteriormente esta nos permite ejecutar de manera repetitiva un bloque de instrucciones sin evaluar de forma inmediata una condición especifica, sino evaluándola justo después de ejecutar por primera vez el bloque de instrucciones.

	do{
		cout<< " Valor de moneda (0.10,0.25): " ;
		cin>>AB_x;
		AB_k=AB_k+ 1 ;
		AB_i=AB_i+AB_x;
		if (AB_x== 10 ){
			AB_k1=AB_k1+ 1 ;
			AB_i1=AB_i1+AB_x;
		} else {
		AB_d2=AB_d2+ 1 ;
		AB_e2=AB_e2+AB_x;
		}
    } while (AB_d<AB_n);
### SALIDA
##### Mostrar resultado:
	cout<< " Nos da como resultado: " <<endl;
  
	cout<< " Valor de monedas digitadas: " <<AB_k<<endl;
  
	cout<< " Valor del dinero sumado: " <<AB_i<<endl;
  
	cout<< " Valor de monedas de 10 digitadas: " <<AB_k1<<endl;
  
	cout<< " Valor de monedas de 10: " <<AB_i1<<endl;
  
	cout<< " Valor de monedas de 25 digitadas: " <<AB_k2<<endl;
  
	cout<< " Valor de monedas de 25: " <<AB_i2<<endl;

### 4) PUNTO DE VENTA
El programa llevara el control de ventas e inventarios sobre el negocio: número de productos vendidos, el valor total de la venta, y el valor de descuento que utilizara.

### FUNCIONALIDAD

##### Declarar variables

int AB_c=0, AB_l;

float AB_x=0, AB_u, AB_p, AB_m, AB_m1, AB_iv, AB_f;
##### Mostrar comentario e ingresar la variable

cout<<"Digite el valor de los producto a sumar"<<endl;

cin>>LJ_b;
##### Luego utilizar la estructura estructura repetitiva para evaluar el valor de la compra y el descuento.

do{

        cout<<"Escriba el valor de su compra "<<AB_c+1<<endl;
	
		cin>>AB_u;
		
		AB_c=AB_c+1;
		
		AB_x=AB_x+AB_u;
		
	}while (AB_c<AB_l);
	
	cout<<"Escriba el valor del descuento que utilizara: "<<endl;
	
	cin>>AB_p;
	
### SALIDA
##### Mostrar resultado

cout<<"Valor bruto de compra: "<<AB_x<<endl;

	AB_m=(AB_x*AB_p)/100;
	
	cout<<"Valor del descuento: "<<AB_m<<endl;
	
	AB_m1=AB_x-AB_m;
	
	AB_iv=AB_m1*0.12;
	
	cout<<"Valor del IVA: "<<AB_iv<<endl;
	
	AB_f=(AB_x-AB_m)+AB_iv;
	
	cout<<"Valor final: "<<AB_f<<endl;
  
### 5) LA EDAD
El programa permitira calcular la edad de una persona, utilizando la fecha actual y la fecha de nacimiento de dicha persona.

### FUNCIONALIDAD

##### Declarar variables

int AB_mm, AB_nn, AB_pp, AB_mm1, AB_nn1, AB_pp1, AB_me, AB_ne, AB_pe;
##### El programa mostrara en pantalla la fecha actual y la fecha de nacimiento usando formato dd/mm/yy (dia-mes-año).

cout<<"Digite la fecha actual usando formato dd/mm/yy: "<<endl;

	cin>>AB_mm>>AB_nn>>AB_pp;
	
	cout<<"Digite su fecha de nacimiento usando formato dd/mm/yy: "<<endl;
	
	cin>>AB_mm1>>AB_nn1>>AB_pp1;
	
##### Utilizando estructura selectiva doble para evaluar una condición.

	if (AB_mm<AB_mm1){
		AB_mm=AB_mm+30;
		AB_nn=AB_nn-1;
		AB_me=AB_mm-AB_mm1;
	}
		else {
			AB_me=AB_mm-AB_mm1;
		}
	if (AB_nn<AB_nn1){
		AB_nn=AB_nn+12;
		AB_pp=AB_pp-1;
		AB_ne=AB_nn-AB_nn1;
	}
		else {
			AB_ne=AB_nn-AB_nn1;
		}
	AB_pe=AB_pp-AB_pp1;
 ### SALIDA
 ##### Mostrar resultado
	cout<<"Usted tiene "<<AB_pe<<" años, "<<AB_ne<<" meses "<<"y "<<AB_me<<" dias."<<endl;
	
## DESCARGAR PROGRAMAS, COPILACION Y EJECUCION DE PROGRAMAS
#### 1) Descargar programas.
Descargar los programas en la aplicacion de termux utilizando el comando:

$ git clone (el link o el codigo del repositorio) 

#### Ejemplo 
$ git clone https://github.com/KarolValen58/Andrea-Ordonez-Programacion.git

#### 2) Compilar programa.
Copilacion del codigo de c++ en termux tilizando el comando:

$ g++ (nombre del codigo de c++ llevando el .cpp)

#### Ejemplo
$ g++ OrdoñezAndrea-comparaN.cpp -o OrdoñezAndrea-comparaN

#### 3) Ejecutar programa.
Ejecucion del programa utilizando el comando:

$ ./(nombre del codigo de c++)

#### Ejemplo
$ ./OrdonezAndrea-comparaN
