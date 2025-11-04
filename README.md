# // Question-1
# include <stdio.h>
int main (){
int i;
char name ;
for(i=0; i<=10; i++)
printf("HELLO SIR \n");
return 0; }

// output 
HELLO SIR 
.
.
.10

// Question-2

#include <stdio.h>
int main() {
    int i, j, rows;
    printf("Enter number of rows: ");
    scanf("%d", &rows);
    for(i = 1; i <= rows; i++) 
    {
        for(j = 1; j <= rows - i; j++)
            printf("   ");
        for(j = 1; j <= (2*i - 1); j++)
            printf(" * ");
        printf("  \n");
    }
    return 0;
}

// output 
                             *
                         *  *  *
                      *  *  *  *  *
                   *  *  *  *  *  *  *
                *  *  *  *  *  *  *  *  *
             *  *  *  *  *  *  *  *  *  *  *
          *  *  *  *  *  *  *  *  *  *  *  *  *
       *  *  *  *  *  *  *  *  *  *  *  *  *  *  *
    *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *
 *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *

//Question-3

#include<stdio.h>

int main(){
int i,n;
printf("Enter Number : ");
scanf("%d",&n);
for (i=0;i<=n;i++)
{
printf("%d\n",i);
}
return 0;
}

//output 

1
2
3
.
.
.100

//Question-4

#include <stdio.h>
int main (){
int a,b;
printf("Enter the number of A : ");
scanf("%d",&a);
printf("Enter the number of B : ");
scanf("%d",&b);
a=a+b;
b=a-b;
a=a-b;
printf("Swap a=%d\nSwap b=%d",a,b);
return 0 ;
}

//output 

Enter the number of A : 13
Enter the number of B : 14
Swap a=14
Swap b=13

//Question-5

// Online C compiler to run C program online
#include <stdio.h>

int main() {
  int a,b,c;
    printf("Enter the value of a :");
scanf("%d",&a);
   printf("Enter the value of b :");
scanf("%d",&b);
   printf("Enter the value of c :");
scanf("%d",&c);
if(a>=b && a>=c){
    printf("Greatest");
}
if(a>=b && a>=c){
    printf("Greatest = %d\n",a);
}
else if(a>=b && a>=c){
    printf("Greatest = %d\n",b);
}
else{
    printf("Greatest = %d\n",c);
}
    return 0;
}

//output 

Enter the value of a :13
Enter the value of b :15
Enter the value of c :16
Greatest = 16
