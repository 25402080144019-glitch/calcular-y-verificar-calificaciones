# calcular-y-verificar-calificaciones
calcular
#include <iostream>
using namespace std ;

int main()
{

float recursos,promedio,indice;
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
