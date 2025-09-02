#include <stdio.h>

int main() {
    float a,b;
   printf("enter two numbers : ");
   scanf("%f %f",&a,&b);
    char c;
   printf("enter operator : ");
   scanf(" %c", &c);
   switch(c) {
       case '+' : printf("%f",a+b);
       break;
       case '-' : printf("%f",a-b);
        break;
       case '*' : printf("%f",a*b);
        break;
       case '/' : if(b!=0){ printf("%f",a/b);}
                  else{printf("value does not exist");}
        break;
        default : printf("invalid operator");
   }   
    return 0;
}
