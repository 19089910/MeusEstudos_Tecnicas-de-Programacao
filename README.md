/* Faça um algoritmo que solicita dois números inteiros ao usuário e exibe a soma dos números e
mostre qual é o maior número.
Faça um algoritmo que solicita a nota do aluno e faz os cálculos no estilo da UNINORTE:
Mensagens que o programa deve informar:
“Aprovado”
“Reprovado””
“Precisa fazer prova final”
Opcional: Informar qual a nota mínima que o aluno precisa ter na prova final.*/
#include <iostream>

using namespace std;

int main() {

	int numero1 , numero2, maior, soma;
	

	cout << "escreva um numero :";
	cin >> numero1;
	cout << "escreva um ssegundo numero :";
	cin >> numero2;
	
	soma << numero1 +numero2;
	
	if (numero1 < numero2){
		numero2 = maior;
	}
		else{ 
		numero1 = maior;
		}
	
	cout << maior;
	
	return 0;
}
