#include <iostream>

using namespace std;

int n1, n2; //Variáveis Globais

int main(){

int n3, n4; //Variáveis Locais

int resultado1; int resultado2; int resultado3;

n1=1977; n2=1991; n3=81; n4=2005;

resultado1=n1+n4;

resultado2=n2+n3;

resultado3=resultado1*resultado2;

cout << "resultado da equação:" << resultado3;

    return 0;
}
