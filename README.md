# calcular-y-verificar-calificaciones
calcular
#include <iostream>
using namespace std ;

int main()
{
    float pro1,pro2,pro3, resultado;
    cout<<"ingrese primer promedio:" ;
    cin>>pro1;
    cout<<"ingrese segundo promedio:" ;
    cin>>pro2 ;
    cout<<"ingrese tercer promedio:" ;
    cin>>pro3 ;
    resultado= (pro1+pro2+pro3)/3 ;
    cout<<"el promedio final es: " <<resultado;
    return 0;
}
