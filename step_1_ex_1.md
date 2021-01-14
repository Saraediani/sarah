```c
#include<stdio.h>
 int main (){
   //afichage infos personels
  printf("info personel : \n \n \n \n");
  char nom [20];
  char prenom[20];
  char sex[20];
  int age ;
  int numero;
  printf("entrer votre nom svp : \n ");
  scanf("%s",nom);
  printf("entrer votre prenom svp : \n ");
  scanf("%s",prenom);
  printf("entrer votre sex svp : \n ");
  scanf("%s",sex);
  printf("entrer votre age svp : \n ");
  scanf("%d",&age);
  printf("entrer votre numero svp : \n ");
  scanf("%d",&numero);  

  printf("bonjour %s %s vous ets une %s age de %d votre numero de telephone et %d",prenom,nom,sex,age,numero);

     return 0;
 }
```
