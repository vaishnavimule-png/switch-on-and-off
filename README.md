# switch-on-and-off
c program

#include <stdio.h>

int main() {
   int choice;
    printf("enter choice:");
    scanf("%d",&choice);
    if("choice==1"){
        printf("turn ON the waterpump\n");
    }
        else if("choice==0"){
            printf("turn OFF the waterpump");
        
        }
          else{
              printf("invalid choice");
          }  
    
    return 0;
}
