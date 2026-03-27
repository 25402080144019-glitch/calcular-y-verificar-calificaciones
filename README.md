# calcular-y-verificar-calificaciones
calcular
#include <iostream>
using namespace std ;

int main()
{

int cal1, cal2, cal3, cal4, cal5, cal6, resultado;
float recursos,promedio,indice,pro1,pro2,pro3;
std::cout<<"ingresa el promedio: ";
std::cin>>promedio;
std::cout<<"ingresa la cantidad de dinero que ingresan en casa: ";
std::cin>>recursos;
indice=recursos+promedio;
if(indice<6000){
std::cout<<"eres candidato para resivir tu beca: " << indice;
    
}else{
cout<<"lamentablemente no eres candidato: ";
}
 return 0;
}
cout<<"ingrese primera calificacion: " ;
    cin>>cal1;
    cout<<"ingrese segunda calificacicion: " ;
    cin>>cal2;
    cout<<"ingrese tercera calificacion: " ;
    cin>>cal3;
    cout<<"ingrese cuarta calificacion: " ;
    cin>>cal4;
    cout<<"ingrese quinta calicacion: " ;
    cin>>cal5;
    cout<<"ingrese sexta calificacion " ;
    cin>>cal6;
    resultado=(cal1+cal2+cal3+cal4+cal5+cal6)/6;
    cout<<"el promedio del parcial es: " <<resultado;
    cout<<"ingrese primer promedio:" ;
    cin>>pro1;
    cout<<"ingrese segundo promedio:" ;
    cin>>pro2 ;
    cout<<"ingrese tercer promedio:" ;
    cin>>pro3 ;
    resultado= (pro1+pro2+pro3)/3 ;
    cout<<"el promedio final es: " <<resultado;
