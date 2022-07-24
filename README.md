# contrase-a-aleatoria
#include <iostream>
#include <time.h>
using namespace std;

int main()
{
	
	srand(time(0));
	string pass;
	
	string data = "qwertyuiopasdfghjklñzxcvbnm"
	              "QWERTYUIOPASDFGHJKLÑZXCVBNM"
	              "1234567890";
	              
	              for (int i = 1; i<=12; i++)
	              {
	              	pass = pass + data [rand() % 93];
	              }
	              cout<<"Tu contraseña es : "<<pass;
	              
	
	
	
	return 0;
}
