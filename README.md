``` python
# Conversiones de unidades de longitud
print("convesiones")
opcion =  int(input("***MENÚ*** /1. centimetros a metros /2. centimetros a yardas /3. centimetros a varas /4. centimetros a pulgadas /5. centimetros a pies "ingrese la opción que desee:")
if opcion == 1:
    print("----------------------------------------")
    opcion=int(input("ingrese la cantidad de centimetros a convertir: "))
    metros = centimetros*0.01
    print(centimetros,"centimetros equivalen a",metros,"metros")
elif opcion == 2:
    print("----------------------------------------")
    opcion=int(input("ingrese la cantidad de centimetros a convertir: "))
    yardas = centimetros*0.0109361
elif opcion == 3:
    print("----------------------------------------")
    opcion=int(input("ingrese la cantidad de centimetros a convertir: "))
    varas = centimetros*0.011963081929167
    print(centimetros,"centimetros equivalen a",varas,"varas")
elif opcion == 4:
    print("----------------------------------------")
    opcion=int(input("ingrese la cantidad de centimetros a convertir: "))
    pulgadas = centimetros*0.393701
    print(centimetros,"centimetros equivalen a",pulgadas,"pulgadas")
elif opcion == 5:
    print("----------------------------------------")
    opcion=int(input("ingrese la cantidad de centimetros a convertir: "))
    pies = centimetros*0.0328084
    print(centimetros,"centimetros equivalen a",pies,"pies")
else:
    print("ingrese una opcion valida")

    
``` Pseudocódigo Algoritmo Unidad_de_longitud
	definir cm Como Real
	definir metros Como Real
	definir yardas Como Real
	definir varas Como Real
	definir pulgadas Como Real
	definir pies Como Real
	Escribir "Muestre los centimetros"
	leer cm
	pies <- cm*0.0328084
	Escribir "los cm convertidos a pies: ",pies
	metros <- cm*0.01
	Escribir "los cm convertidos a metros: ",metros
	yardas <- cm*0.0109361
	Escribir "los cm convertidos a yardas: ",yardas
	varas <- cm*0.011963081929167
	Escribir "los cm convertidos a yardas: ",varas
	pulgadas <- cm*0.393701
	Escribir "los cm convertidos a pulgadas: ",pulgadas
FinAlgoritmo


``` C++
/*Conversiones de Unidades de Longitud
#include <iostream>
using namespace std;
int main(void){
    int opcion;
    double cm, metros, yardas, varas, pulgadas, pies;

    cout <<"Ingrese una opción: " << enld;
    cout <<"1. cm a metros " << enld;
    cout <<"2. cm a yardas " << enld;
    cout <<"3. cm a varas " << enld;
    cout <<"4. cm a pulgadas " << enld;
    cout <<"5. cm a pies " << enld;
    cin >> opcion;

    switch  (opcion){
        case 1:
            cout << "---cm a metros---" << endl;
            cout << "Ingrese la cantidad de cm a convertir: " <<endl;
            cin >> cm;
            metros=cm*0.01;
            cout << cm << " cm equivalen a " << metros << " metros." <<endl;
            break;
        case 2:
            cout << "---cm a yardas---" << endl;
            cout << "Ingrese la cantidad de cm a convertir: " <<endl;
            cin >> cm;
            yardas=cm*0.0109361;
            cout << cm << " cm equivalen a " << yardas << " yardas." <<endl;
            break;
        case 3:
            cout << "---cm a varas---" << endl;
            cout << "Ingrese la cantidad de cm a convertir: " <<endl;
            cin >> cm;
            metros=cm*0.011963081929167;
            cout << cm << " cm equivalen a " << varas << " varas." <<endl;
            break;
        case 4:
            cout << "---cm a pulgadas---" << endl;
            cout << "Ingrese la cantidad de cm a convertir: " <<endl;
            cin >> cm;
            metros=cm**0.393701;
            cout << cm << " cm equivalen a " << pulgadas << " pulgadas." <<endl;
            break;
        case 5:
            cout << "---cm a pies---" << endl;
            cout << "Ingrese la cantidad de cm a convertir: " <<endl;
            cin >> cm;
            pies=cm*0.0328084;
            cout << cm << " cm equivalen a " << pies << " pies." <<endl;
            break;

        cout << endl;
        return 0;

```
