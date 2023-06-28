# array
#include <iostream>
#include <conio.h>
using namespace std;
/*pida al usuario un vector de 4 numeros luego mueste el numero en pantalla  y calcule la suma de sus elementos*/ 

int SumaElementosVec (int const vector[] , int tam=4)
{
    int  suma=0;
    for(int i=0; i<4; i++)
        {
            suma += vector [i];
        }
    return suma;
}
 int main()
{ 
    int vector [4];
    cout<<"ingrese los numeros que quiere que pertenezcan al vector unidemensional 4"<<endl;
    for (int i=0; i<4; i++)
    {
        cout<<"digite un numero"<<endl;
        cin>>vector [i];
    }
    cout<<"El resultado de la suma de los elementos del vector es "<<SumaElementosVec(vector,4)<<endl;
    return 0;
}

