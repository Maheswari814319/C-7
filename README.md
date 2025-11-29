# C-7
Program to take user- define input
#include<stdio.h>
int main(){
int maheswari[9];
int i, sum=0;
printf("enter 5 integers:");
for(i=0;i<9;i++){
scanf("%d", &maheswari[i]);
}
for(i=0;i<9;i++){
sum += maheswari[i];
}
printf("sum : %d", sum);
return 0;
}
