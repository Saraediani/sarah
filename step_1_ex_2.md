#include<stdio.h>
   void main (){
   	int a,b;
   	printf("entrer un nombre A : \n");
   	scanf("%d",&a);
   	printf("entre un nombre B : \n");
   	scanf("%d",&b);
   	
   	int add=a+b ;
   	int soust=a-b;
   	int mult=a*b;
   	int div=(float)a/b;    	
   	
   	printf("le nombre de %d + le nombre de %d egal :%d \n",a,b,add);
   	printf("le nombre de %d - le nombre de %d egal :%d \n",a,b,soust);
   	printf("la nombre de %d * le nombre de %d egal :%d \n",a,b,mult);
   	printf("la nombre de %d / le nombre de %d egal :%d \n",a,b,div);
   	
   }
