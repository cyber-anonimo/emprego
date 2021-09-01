# emprego
#include<iostream>
using namespace std;
  
  int main(){
	
	int salario = 0;	
	
	 cout << "Digite o valor de um salario($): ";
	   cin >> salario;

	 if(salario > 1900){
	 	cout << "Usuario devera pagar 2% de imposto.";
	 }else if(salario > 2500){
	 	cout << "Usuario devera pagar 3% de imposto.";
	 }else if(salario > 3700){
	 	cout << "Usuario devera pagar 4,5% de imposto.";
	 }else if(salario > 5000){
	 	cout << "Usuario devera pagar 6% de imposto.";
	 }else{
	 	cout << "Usuario nao precisa pagar nada.";
	 }
	 
	   
return 0;	
} 
