# calcular-y-verificar-calificaciones
calcular
#include <iostream>
using namespace std;

int main()
{
   
 float promedio,pro1,pro2,pro3,resultado,recursos,indice; 
 int op,cal1,cal2,cal3,cal4,cal5,cal6; 
  cout<<"escribe el numero de la opcion que necesitas: "<<endl;
  cout<<"1.promedio semestral: "<<endl;
  cout<<"2.promedio del parcial: "<<endl;
  cout<<"3.merecedor de la beca: "<<endl;
  cin>>op;
  
  if(op==1){
  cout<<"ingresa el primer promedio: ";
  cin>>pro1;
  cout<<"ingresa el segundo promedio: ";
  cin>>pro2;
  cout<<"ingresa el tercer promedio: ";
  cin>>pro3;
  resultado=(pro1+pro2+pro3)/3;
  cout<<"el promedio final es: "<<resultado;
  }else if(op==2){
      
  cout<<"ingresa primera calificacion: ";
  cin>>cal1;
  cout<<"ingresa sedunda calificacin: ";
  cin>>cal2;
  cout<<"ingresa tercera calificacion: "; 
  cin>>cal3; 
  cout<<"ingresa cuarta calificacin: "; 
  cin>>cal4; 
  cout<<"ingresa quinta calificacion: ";
  cin>>cal5;
  cout<<"ingresa sexta calificacion: ";
  cin>>cal6;
  promedio=(cal1+cal2+cal3+cal4+cal5+cal6)/6;
  cout<<"el promedio del parcial es: "<<promedio;
  }else if(op==3){
      
  cout<<"ingresa el promedio: ";
  cin>>promedio;
  cout<<"ingresa la cantidad de dinero que ingresa tu casa: ";
  cin>>recursos;
  indice=recursos+promedio;
  if(indice<6000){
  cout<<"eres candidato para recibir tu beca: ";
  }else{cout<<"lo siento no eres candidato: ";}
  }else{
  cout<<"opcion no valida: ";
  }
    return 0;
}
