school-repository
=================

my thirst repository

//Um exemplo de chamar métodos, reutilização...
// receber 3 numeros
// calcular a media
// informar maior e menor
 #include <stdio.h>
 #include <stdlib.h>
 int recebeDado();
 int soma(int,int);
 
 int main(){
     printf("O valor informado foi %.2f",(float)soma(soma(recebeDado(), recebeDado()),recebeDado())/3);
     system("pause");
     }
     int soma(int a, int b){
         return a + b;
         }
     int recebeDado(){
         int n;
         printf("informe um numero");
         scanf("%d",&n);
         return n;
         }

