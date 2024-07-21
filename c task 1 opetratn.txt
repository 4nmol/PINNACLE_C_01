#include<stdio.h>
#include<stdlib.h>

int main()
{
    while(1)
    {
        int n;
        printf("Press 1 for Addition\n");
        printf("Press 2 for Substraction\n");
        printf("Press 3 for Multiplication\n");
        printf("Press 4 for Division\n");
        printf("Press 5 for Exit the console\n");
        printf("Enter the above number keys to perform operation\n");
        scanf("%d",&n);
        switch(n)
        {
            case 1:
                int a1,b1,add;
                printf("enter the two numbers for Addition\n");
                scanf("%d%d",&a1,&b1);
                add=a1+b1;
                printf("Addition of two numbers is %d\n",add);
                break;
            case 2:
                int a2,b2,sub;
                printf("enter the two numbers for Substraction\n");
                scanf("%d%d",&a2,&b2);
                sub=a2-b2;
                printf("Substraction of two numbers is %d\n",sub);
                break;
            case 3:
                int a3,b3,mul;
                printf("enter the two numbers for Multiplication\n");
                scanf("%d%d",&a3,&b3);
                mul=a3*b3;
                printf("Multiplication of two numbers is %d\n",mul);
                break; 
            case 4:
                int a4,b4;
                float divi;
                printf("enter the two numbers for Division\n");
                scanf("%d%d",&a4,&b4);
                divi=a4/b4;
                printf("Division of two numbers is %0.2f\n",divi);
                break;
            case 5:
                exit(0);
                
        }   
    }
}