**ASSIGNMENT OPERATOR:**



\#include<stdio.h>

int main(){

&#x20;   int i=10;

&#x20;   i+=9;

&#x20;   printf("%d\\n",i);

&#x20;   i-=9;

&#x20;   printf("%d\\n",i);

&#x20;    i\*=9;

&#x20;   printf("%d\\n",i);

&#x20;   i/=9;

&#x20;   printf("%d\\n",i);

&#x20;   i%=9;

&#x20;   printf("%d\\n",i);

&#x20;   return 0;

}





\#include<stdio.h>

int main(){

&#x20;   int a,b;

&#x20;   printf("Enter:");

&#x20;   scanf("%d %d",\&a,\&b);

&#x20;   printf("%d\\n",a+=b);

&#x20;   printf("%d\\n",a-=b);

&#x20;   printf("%d\\n",a\*=b);

&#x20;   printf("%d\\n",a/=b);

&#x20;   printf("%d\\n",a%=b);

return 0;



}



**relational operation:**



\#include<stdio.h>

int main(){

&#x20;   int a,b;

&#x20;

&#x20;   scanf("%d %d",\&a,\&b);

&#x20;  printf("%d\\n",a>b);

&#x20;  printf("%d\\n",a<b);

return 0;



}



\#include<stdio.h>

int main(){

&#x20;   int a,b;

&#x20;

&#x20;   scanf("%d %d",\&a,\&b);

&#x20;  printf("%d\\n",a>b);

&#x20;  printf("%d\\n",a<b);

&#x20;  printf("%d\\n",a>=b);

printf("%d\\n",a<=b);

printf("%d\\n",a!=b);

printf("%d\\n",a==b);

return 0;



}



**logical:**



\#include<stdio.h>

int main(){

&#x20;   int age=25;

&#x20;   printf("%d\\n",age>18\&\&age<60);

&#x20;   printf("%d\\n",age>18||age<20);

&#x20;   printf("%d\\n",!(age<60));

return 0;



}





**if condition**





\#include<stdio.h>

int main(){

&#x20;   int age;

&#x20;   printf("enter age:");

&#x20;   scanf("%d",\&age);

&#x20;   if(age>=18){

&#x20;       printf("eligible to vote");

&#x20;   }

&#x20;   else{

&#x20;       printf("Not eligible");

&#x20;   }

&#x20;

}



\#include<stdio.h>

int main(){

&#x20;   int number=25;

&#x20;   if(number%2==0){

&#x20;       printf("even");

&#x20;   }

&#x20;   else{

&#x20;       printf("odd");

&#x20;   }

&#x20;

}





\#include<stdio.h>

int main(){

&#x20;   int number=25;

&#x20;   if(number<0){

&#x20;       printf("negative");

&#x20;   }

&#x20;   else{

&#x20;       printf("positive");

&#x20;   }

&#x20;   }





\#include<stdio.h>



int main() {

&#x20;   int unit;

&#x20;   scanf("%d",\&unit);



&#x20;   if(unit == 300) {

&#x20;       printf("%d", unit \* 30);

&#x20;   }

&#x20;   else {

&#x20;       printf("%d", unit \*40);

&#x20;   }



&#x20;   return 0;

}





\#include<stdio.h>



int main() {

&#x20;   int unit;

&#x20;   float bill;

&#x20;   scanf("%d",\&unit);



&#x20;   if(unit <= 300) {

&#x20;      bill=unit \* 30;

&#x20;   }

&#x20;   else if(unit>=300||unit<=300){

&#x20;       bill=unit\*20;

&#x20;   }

&#x20;   else {

&#x20;     bill= unit \*40;

&#x20;   }

printf("bill:%f",bill);

&#x20;   return 0;

}





\#include <stdio.h>



int main() {

&#x20;   int a,b,c;

&#x20;   scanf("%d %d %d",\&a,\&b,\&c);

&#x20;   if((a>b)\&\&(a>c)){

&#x20;       printf("A is greater");

&#x20;   }

&#x20;   else if((b<c)){

&#x20;       printf("c is greater");

&#x20;   }

&#x20;   else{

&#x20;       printf("b is greater");

&#x20;   }

}







\#include <stdio.h>



int main() {

&#x20;   int a,b,c;

&#x20;   scanf("%d %d %d",\&a,\&b,\&c);

&#x20;   if((a<b)\&\&(a<c)){

&#x20;       printf("A is lesser");

&#x20;   }

&#x20;   else if((b<c)){

&#x20;       printf("b is lesser");

&#x20;   }

&#x20;   else{

&#x20;       printf("c is lesser");

&#x20;   }

}





**for condition**





\#include<stdio.h>

int main(){

&#x20;   int i,n;

&#x20;

&#x20;   scanf("%d",\&n);

&#x20;   printf("NUM\\t SQUARE\\t CUBE\\n");

&#x20;   for(i=11;i<=n;i++){

&#x20;       printf("%d\\t%d\\t%d\\n",i,i\*i,i\*i\*i);

&#x20;   }

}





**Floyd's triangle**



\#include <stdio.h>



int main() {

&#x20;   int n, num = 1;



&#x20;   printf("Enter the number of rows: ");

&#x20;   scanf("%d", \&n);



&#x20;   for(int i = 1; i <= n; i++) {

&#x20;       for(int j = 1; j <= i; j++) {

&#x20;           printf("%d ", num);

&#x20;           num++;

&#x20;       }

&#x20;       printf("\\n");

&#x20;   }



&#x20;   return 0;

}





\#include <stdio.h>



int main() {

&#x20;   int n;

&#x20;   scanf("%d",\&n);

&#x20;   if(n<25){

&#x20;       printf("too less");

&#x20;   }else if(n==25){

&#x20;       printf("you win");

&#x20;   }

&#x20;   else{

&#x20;       printf("too large");

&#x20;   }

&#x20;   }







**Fibonacci**



\#include <stdio.h>



int main() {

&#x20;   int a = 0, b = 1, c, n = 10;



&#x20;   printf("%d %d ", a, b);



&#x20;   for(int i = 3; i <= n; i++) {

&#x20;       c = a + b;

&#x20;       printf("%d ", c);



&#x20;       a = b;

&#x20;       b = c;

&#x20;   }



&#x20;   return 0;

}





**pattern:**



\#include<stdio.h>

int main(){

&#x20;   int i,j;

&#x20;   for(i=0;i<6;i++){

&#x20;       for(j=0;j<7;j++){

&#x20;           if((i==0 \&\& j%3 != 0)||

&#x20;           (i==1 \&\& j%3 == 0)||

&#x20;           (i - j == 2) ||

&#x20;           (i+j == 8)){

&#x20;               printf("\*");

&#x20;           }

&#x20;           else{

&#x20;               printf(" ");

&#x20;           }

&#x20;           }

&#x20;         printf("\\n");

&#x20;       }

&#x20;       return 0;

&#x20;   }



**switch case:**



\#include <stdio.h>



int main() {

&#x20;   char choice;

&#x20;   int a = 10, b = 15;



&#x20;   scanf("%c", \&choice);



&#x20;   switch(choice) {

&#x20;       case '+':

&#x20;           printf("%d", a + b);

&#x20;           break;



&#x20;       case '-':

&#x20;           printf("%d", a - b);

&#x20;           break;



&#x20;       case '/':

&#x20;           printf("%d", a / b);

&#x20;           break;



&#x20;       case '\*':

&#x20;           printf("%d", a \* b);

&#x20;           break;



&#x20;       default:

&#x20;           printf("Invalid Operator");

&#x20;   }



&#x20;   return 0;

}





**array:**



\#include<stdio.h>

int main(){

&#x20;   int a\[3];

&#x20;   char b\[3];

&#x20;   float c\[3];

&#x20;   char d\[6] ="hello";

&#x20;   printf("int array=%lu bytes\\n",sizeof(a));

&#x20;   printf("char array=%lu bytes\\n",sizeof(b));

&#x20;   printf("float array=%lu bytes\\n",sizeof(c));

&#x20;   printf("string array=%lu bytes\\n",sizeof(d));

&#x20;   return 0;

}



**2 dimensional array:**



\#include<stdio.h>

int main(){

&#x20;   int arr\[2]\[2]={{1,2},{3,4}};

&#x20;   printf("%d %d",arr\[0]\[0],arr\[1]\[1]);

&#x20;   return 0;

}



**matrix:**



\#include<stdio.h>

int main(){

&#x20;   int arr\[2]\[3]={{1,2,3},{4,5,6}};

&#x20;   for(int i=0;i<2;i++){

&#x20;       for(int j=0;j<3;j++){

&#x20;           printf("%d",arr\[i]\[j]);



&#x20;       }

&#x20;       printf("\\n");

&#x20;   }

}



**ADDITION:**



\#include<stdio.h>

int main(){

&#x20;   int a\[2]\[2]={{1,2},{3,4}};

&#x20;   int b\[2]\[2]={{5,6},{7,8}};

&#x20;   int c\[2]\[2];

&#x20;   for(int i=0;i<2;i++){

&#x20;       for(int j=0;j<2;j++){

&#x20;           c\[i]\[j]=a\[i]\[j]+b\[i]\[j];

&#x20;           printf("%d\\n",c\[i]\[j]);



&#x20;       }

&#x20;       //printf("\\n");

&#x20;   }

}



**string:**







\#include<stdio.h>

int main(){

&#x20;   char str\[100];

&#x20;   int length = 0;

&#x20;   printf("Enter a string:");

&#x20;   scanf("%s",str);

&#x20;   while(str\[length]!='\\0')

&#x20;   {

&#x20;       length++;

&#x20;   }

&#x20;   printf("length of string=%d",length);

&#x20;   }





**reverse:**



\#include<stdio.h>

int main(){

&#x20;   char str\[100];

&#x20;   int length = 0;

&#x20;   printf("Enter a string:");

&#x20;   scanf("%s",str);

&#x20;   while(str\[length]!='\\0')

&#x20;   {

&#x20;       length++;

&#x20;   }

&#x20;   printf("reversed string: ");

&#x20;   for(int i=length-1;i>=0;i--){

&#x20;       printf("%c",str\[i]);

&#x20;   }

&#x20;   return 0;

&#x20;    }



**2 table:**





\#include<stdio.h>

int main(){

&#x20;   int i;

&#x20;   for(i=1;i<=10;i++){

&#x20;       printf("2 x %d =%d\\n",i,2\*i);

&#x20;   }

&#x20;   return 0;

&#x20;    }



FUNCTION:

\#include<stdio.h>

void greet()

{

&#x20;   printf("Hello World\\n");

&#x20;

}

int main()

{

&#x20;   greet();

&#x20;   return 0;

&#x20;

}

no arguments,no return value:

\#include<stdio.h>

void add()

{

&#x20;   int a=10,b=20;

&#x20;   printf("Sum=%d",a+b);

&#x20;

}

int main()

{

&#x20;   add();

&#x20;   return 0;

&#x20;

}

arguments,no return value



\#include<stdio.h>

void add(int a,int b)

{

&#x20;

&#x20;   printf("Sum=%d",a+b);

&#x20;

}

int main()

{

&#x20;   add(10,20);

&#x20;   return 0;

&#x20;

}

no arguments,return value

\#include<stdio.h>

int add()

{

&#x20;   int a=10,b=20;

&#x20;   return a+b;



}

int main()

{

&#x20;   printf("Sum=%d",add());

&#x20;   return 0;

&#x20;

}



arguments,return value

\#include<stdio.h>

int add(int a,int b)

{

&#x20;

&#x20;   return a+b;



}

int main()

{

&#x20;   int result=add(10,20);

&#x20;   printf("Sum=%d",result);

&#x20;   return 0;

&#x20;

}



function structure

\#include<stdio.h>

int add(int ,int);

int main()

{

&#x20; int result=add(10,20);

&#x20; printf("Result=%d",result);

&#x20; return 0;



}

int add(int a,int b)

{

&#x20;   return a+b;

&#x20;

}

recursion factorial:



\#include<stdio.h>

int factorial(int n)

{

&#x20;   if(n==0||n==1)

&#x20;   return 1;

&#x20;   return n\*factorial (n-1);

}

int main()

{

&#x20;   int num=5;

&#x20;   printf("Factorial=%d",factorial(num));

&#x20;   return 0;

}
kadane's algorithm:

\#include<stdio.h>

int arr\[]={-2,-3,4,-1,-2,1,5,-3};

int maxSum=arr\[0];

int currentSum=0;

for(int i=0;i<n;i++){

&#x20;   currentSum += arr\[i];

&#x20;   if(currentSum>maxSum)

&#x20;   maxSum=currentSum;

&#x20;   if(currentSum<0)

&#x20;   currentSum =0;

}



sum:

\#include <stdio.h>



int main() {

&#x20;   int arr\[] = {-2, -3, 4, -1, -2, 1, 5, -3};



&#x20;   int n = sizeof(arr) / sizeof(arr\[0]);



&#x20;   int maxSum = arr\[0];

&#x20;   int currentSum = 0;



&#x20;   for(int i = 0; i < n; i++) {

&#x20;       currentSum += arr\[i];



&#x20;       if(currentSum > maxSum)

&#x20;           maxSum = currentSum;



&#x20;       if(currentSum < 0)

&#x20;           currentSum = 0;

&#x20;   }



&#x20;   printf("Maximum Sum = %d", maxSum);



&#x20;   return 0;

}

file handling:



\#include <stdio.h>



int main()

{

&#x20;   FILE \*fp;

&#x20;   char ch;



&#x20;   // WRITE MODE

&#x20;   fp = fopen("sample.txt", "w");

&#x20;   fprintf(fp, "Hello C Programming\\n");

&#x20;   fclose(fp);



&#x20;   // APPEND MODE

&#x20;   fp = fopen("sample.txt", "a");

&#x20;   fprintf(fp, "File Handling Concept\\n");

&#x20;   fclose(fp);



&#x20;   // READ MODE

&#x20;   fp = fopen("sample.txt", "r");



&#x20;   printf("File Content:\\n");



&#x20;   while((ch = fgetc(fp)) != EOF)

&#x20;   {

&#x20;       printf("%c", ch);

&#x20;   }



&#x20;   fclose(fp);



&#x20;   return 0;

}



pointer:



\#include <stdio.h>

int main() {

&#x20;   int num=100;

&#x20;   int \*ptr=\&num;

&#x20;   printf("value=%d\\n",num);

&#x20;   printf("Address=%p\\n",\&num);

&#x20;   printf("using pointer=%d\\n",\*ptr);

&#x20;   printf("using pointer=%p\\n",ptr);

&#x20;

&#x20;   return 0;

}

pointer to pointer:
#include <stdio.h>

//a pointer stores the address of another pointer

int main() {

&#x20;   int a=10;

&#x20;   int \*p=\&a;

&#x20;   int\*\*pp=\&p;

&#x20;   printf("%d\\n",\*\*pp);

&#x20;   printf("%p",\*pp);

&#x20;

&#x20;   return 0;

}

**MINI PROJECT:**

**bank management system hw**:

\#include <stdio.h>



int balance = 5000;



void deposit()

{

&#x20;   int amt;

&#x20;   printf("Enter amount: ");

&#x20;   scanf("%d", \&amt);

&#x20;   balance += amt;

}



void withdraw()

{

&#x20;   int amt;

&#x20;   printf("Enter amount: ");

&#x20;   scanf("%d", \&amt);



&#x20;   if(amt <= balance)

&#x20;       balance -= amt;

&#x20;   else

&#x20;       printf("Insufficient balance\\n");

}



void showBalance()

{

&#x20;   printf("Balance = %d\\n", balance);

}



int main()

{

&#x20;   int choice;



&#x20;   printf("1. Deposit\\n");

&#x20;   printf("2. Withdraw\\n");

&#x20;   printf("3. Balance\\n");



&#x20;   printf("Enter choice: ");

&#x20;   scanf("%d", \&choice);



&#x20;   switch(choice)

&#x20;   {

&#x20;       case 1:

&#x20;           deposit();

&#x20;           showBalance();

&#x20;           break;



&#x20;       case 2:

&#x20;           withdraw();

&#x20;           showBalance();

&#x20;           break;



&#x20;       case 3:

&#x20;           showBalance();

&#x20;           break;



&#x20;       default:

&#x20;           printf("Invalid Choice");

&#x20;   }



&#x20;   return 0;

}



