# C-LANGUAGE-CONTENT


CHAPTER 1 C LANGUAGE


									DOUBLE USE OF printf


#include <stdio.h>

int main() {
    int age;

    printf("ENTER age");
    scanf("%d", & age);

    printf("THE age IS %d",age);
    return 0;
}

or

#include <stdio.h>

int main() {
    int a,b;
    printf("ENTER a");
    scanf("%d", & a);
    
    printf("ENTER b %d",b);
    scanf("%d",&b);
    
    printf("THE SUM OF a AND b IS %d",a+b);
    return 0;
}
or 

#include <stdio.h>

int main() {
    int length;
    printf("ENTER length");
    scanf("%d", & length);
    
    printf("THE AREA OF THE GIVEN SQUARE %d",length*length);
    return 0;
}


or 

#include <stdio.h>

int main() {
    int a = 8;
    printf("%d", a);
    
    float b = 2.2;
    printf("%f", b);
    
    char c = 't';
    printf("%c", c);
    return 0;
}

or
   									USES OF CHAR , FLOAT AND PRINT
#include <stdio.h>
    int main(){
        
    int a = 500000000;   
    printf("THE MONEY IN THE BANK IS %d\n",a);
    
    float b = 7.7;
    printf("THE VALUE OF KAPIL MALI IS %f BILLION DOLLORS \n",b);
    
    char S = 'K';
    printf("the value of S is %c",S);
    return 0;
    
    return 0;
    }

or 

#include <stdio.h>

int main() {
    int a = 8;
    printf("%d", a);
    
    float b = 2.2;
    printf("%f", b);
    
    char c = 't';
    printf("%c", c);
    
    printf("kapil is a great \n person ");
    return 0;
}

or

uses of \n , \t , \\ , \'
#include <stdio.h>

int main() {
    int a = 8;
    printf("%d", a);
    
    float b = 2.2;
    printf("%f", b);
    
    char c = 't';
    printf("%c", c);
    
    printf("kapil \\is \'a \t great \n person ");
    return 0;
}

or 

									how to write in different lines the values of a and b
#include <stdio.h>

int main() {
    int a = 1;
    int b = 2;
    printf("%d\n",a);
    printf("%d",b);
    return 0;
}

or 

										uses of int,float and char
#include <stdio.h>

int main() {
    int a = 8;
    float b = 2.2;
    char c = 't';
    
    printf("%d\n", a);
    printf("%f\n", b);
    printf("%c\n", c);
    return 0;
}

									IT CAN ALSO BE WRITTEN IN THIS FORM
#include <stdio.h>

int main() {
    int a = 8;
       printf("%d\n", a);
       
    float b = 2.2;
        printf("%f\n", b);
        
    char c = 't';
        printf("%c\n", c);
        
    return 0;
}

or

									PRACTICE SET 
									QUESTION NO 1
									ANSWER NO 1(A)
#include <stdio.h>

int main() {
    int length = 3;
    int breadth = 6;
    printf("the area of rectangle is %d",length*breadth);
    return 0;
}

or

									PRACTICE SET 
									QUESTION NO 1
									ANSWER NO 1(B)

#include<stdio.h>
int main(){
    
    int length ;
    int breadth ;
    
    printf (" ENTER THE LENGTH OF THE RECTANGLE \n");
    scanf ("%d",&length);
    
    printf (" ENTER THE BREADTH OF THE RECTANGLE \n");
    scanf ("%d",&breadth);
    
    printf("THE AREA OF THE RECTANGLE IS %d", length*breadth);
    
    return 0;
}

LEARNING : USE %d in printf only when we have to print something not when we want to just want to show something on the screen, that's why we have used %d in the last printf only.

or 

									PRACTICE SET 
									QUESTION NO 2.1


#include<stdio.h>
int main(){
    
    float radius = 8.0;
    
    printf("THE AREA OF A CIRCLE WITH RADIUS %f IS %f",radius ,3.14 * radius * radius);
    
}



									ANSWER NO 2.2


#include<stdio.h>
int main(){
    
    float radius = 8.0;
    float height = 5.0;
    
    printf("THE AREA OF A CIRCLE WITH RADIUS %f IS %f \n",radius ,3.14 * radius * radius);
    
    printf("THE VOLUME OF A CYLINDER WITH RADIUS %f AND HEIGHT %f IS : %f",radius , height , 3.14 * radius * radius * height);
    
}
or

										PRACTICE SET 
										QUESTION NO 3
										ANSWER NO 3
#include<stdio.h>
int main(){
    
    float celcius;
    printf ("ENTER YOUR VALUE OF CELCIUS ");
    scanf ("%f",&celcius);
    
    printf ("THE CONVERTED VALUE OF CELCIUS %f INTO FEHRENHEIT IS %f", celcius , (9.0/5.0) * celcius + 32.0);
    
    return 0;
}

or 


											PRACTICE SET 
											QUESTION NO 4
											ANSWER NO 4
#include<stdio.h>
int main(){
    
    float principal_amount;
    float number_of_years;
    float rate_of_interest;
    
    printf ("ENTER YOUR PRINCIPAL AMOUNT ");
    scanf ("%f",&principal_amount);
    
    printf ("ENTER THE NUMBER OF YEARS ");
    scanf ("%f",&number_of_years);
    
    printf ("ENTER THE RATE OF INTEREST ");
    scanf ("%f",&rate_of_interest);
    
    printf ("YOUR SIMPLE INTEREST WILL BE %.2f",(principal_amount * number_of_years * rate_of_interest)/100);

return 0;
    
}


CHAPTER 3 C LANGUAGE


									CHAPTER 3


or
 
                                                                     DECISION MAKING INSTRUCTION IN C
#include <stdio.h>

int main() {
    int age = 5;
    if(age >10){
        
    printf("your age is greater than 10");
    }
    return 0;
}


									CODE WRITTEN DURING PRACTICE



#include<stdio.h>
int main (){
    
    int age;
    printf ("ENTER A NUMBER");
    scanf ("%d",&age);
    
    if(age >0 && age < 18){
        printf ("YOU CANNOT VOTE");
    }
    
    else if(age > 18 && age < 50){
    printf ("YOU CAN VOTE");
    }
    
    else if(age >50 && age < 60 ){
    printf ("YOU ARE ELDER CITIZEN YOU CAN SURELY VOTE");
    }
    
    else{
    printf ("YOU ARE A SENIOR CITIZEN YOU CAN VOTE ");
    }
    
    return 0;
    
}





                                                                    ANOTHER USE OF THE SAME CONCEPT

#include <stdio.h>

int main() {
    int age = 15;
    if(age > 10){
        
    printf("your age is greater than 10");
    }
    return 0;
}

OUTPUT HERE WILL BE
your age is greater than 10

or

                                                                    ANOTHER USE OF THE SAME CONCEPT

#include <stdio.h>

int main() {
    int age = 15;
    if(age >10){
        
    printf("your age is greater than 10\n");
    }
    if(age%5==0){
    printf("your age is divisible by 5");
        
    }
    return 0;
}

or

                                                                    ANOTHER USE OF THE SAME CONCEPT
#include <stdio.h>

int main() {
    int age = 5;
    if(age > 10){
        
    printf("your age is greater than 10\n");
    }
    else{
    printf("your age is not greater than 10\n");
    }
    
    if(age%5==0){
    printf("your age is divisible by 5\n");
    }
    else{
    printf("your age is not divisible by 5");
    
    }
    return 0;
}

or 


                                                                    ANOTHER USE OF THE SAME CONCEPT

#include <stdio.h>

int main() {
    int age = 23;
    if(age >10){
        
    printf("your age is greater than 10\n");
    }
    else{
    printf("your age is not greater than 10\n");
    }
    
    if(age%5==0){
    printf("your age is divisible by 5\n");
    }
    else{
    printf("your age is not divisible by 5");
    
    }
    return 0;
}

or 

										RELATIONAL OPERATORS 
#include <stdio.h>

int main() {
    int a = 100;
    int b = 50;
    
    if (a != 100){
        printf ("THE VALUE OF a IS TRUE ");
    }
    
    else{
        printf ("THE VALUE OF a IS NOT TRUE ");
    }
    
    return 0;
}


									CODE FOR LEARNING THE USE OF ! OPERATOR

#include<stdio.h>
int main (){
    
    int a;
    printf ("ENTER A NUMBER");
    scanf("%d",&a);
    
    if (a == 50){
        printf(" YOUR ENTERED NUMBER IS CORRECT ");
    }
    else if(a !=50)
    {
        printf ("YOUR ENTERED NUMBER IS NOT CORRECT ");
    }
    
    return 0;
}






                                               					LOGICAL OPERATORS
EXAMPLE1 
#include <stdio.h>

int main() {
    int a = 1 , b = 1;
    printf("the value of a and b is %d\n",a&&b);
    printf("the value of a or b is %d\n",a||b);
    printf("the value of not(a) is %d",!a);

    return 0;
}



OR

										ELSE IF OPERATORS




#include <stdio.h>

int main() {
    int age = 19;

    if(age>60){
    printf("YOU CAN DRIVE YOU ARE ELDER");
    }
    else if (age>18){
    printf("YOU CAN DRIVE");
    }
    
    else{
        printf("YOU CANNOT DRIVE");
    }
    
    return 0;

}								

										ANOTHER USE OF THE ABOVE CONCEPT
										MAIN USE OF THE ABOVE CONCEPT [ONLY ONE BLOCK WILL RUN FROM]


#include <stdio.h>

int main() {
    int age = 11;
    
    if(age>60){
    printf("YOU CAN DRIVE YOU ARE SENIOR CITIZEN");
    }
 
    else if (age>40){
    printf("YOU CAN DRIVE YOU ARE ELDER");
    }   
    
    
    else if (age>18){
    printf("YOU CAN DRIVE");
    }
    
    else{
        printf("YOU CANNOT DRIVE");
    }
    
    return 0;
}


									SHORTCUT FOR IF ELSE
#include <stdio.h>

int main() {
    int a = 11;
    int v = 55;
    
    a>v? printf("a is greater"):printf("v is greater");
    
    return 0;
}

or
                                                        		QUICK QUIZ:


QUESTION
WRITE A PROGRAM TO FIND GRADE OF A STUDENT GIVEN HIS MARKS BASED ON BELOW:
PAGE NO.20


								THE BEST AND LOGICAL FORM TO WRITE THE PROGRAM


 
#include <stdio.h>

int main() {

    char grade;
    int marks;
    printf ("ENTER marks");
    scanf ("%d",&marks);
    printf ("the grade is: %c\n",grade);
    
    if (marks<=100 && marks>=90){
        grade = 'A';
    }
    else if (marks<=90 && marks>=80){
        grade = 'B';
    }
    else if (marks<=80 && marks >=70){
        grade = 'C';
    }
    else if (marks<=70 && marks >=60){
        grade = 'D';
    }
    else if (marks<=60 && marks >=50){
        grade = 'E';
    }
    else{
        grade = 'F';
    }

    printf ("the grade is: %c\n",grade)

    return 0;
}





										SWITCH CONCEPT

#include <stdio.h>

int main() {
    int a;
    printf("ENTER a:");
    scanf("%d",&a);
    
    switch(a){
        case 1:
            printf("YOU ENTERED 1");
            break;
        case 2:
            printf("YOU ENTERED 2");
            break;
        case 3:
            printf("YOU ENTERED 3");
            break;
        case 4:
            printf("YOU ENTERED 4");
            break;
        default:
            printf("NOTHING MATCHED");
    }

    return 0;
}
								PRACTICE SET 3
								QUESTION NO.2

#include <stdio.h>

int main() {
    int marks1;
    int marks2;
    int marks3;
    
    printf ("ENTER marks1:\n");
    scanf ("%d",& marks1);
    printf ("ENTER marks2:\n");
    scanf ("%d",& marks2);
    printf ("ENTER marks3:\n");
    scanf ("%d",& marks3);
    
    printf("THE MARKS ARE %d,%d,AND %d\n",marks1,marks2,marks3);
    
    if (marks1<33 || marks2<33 || marks3<33){
        printf("YOU ARE FAILED DUE TO LESS MARKS IN INDIVIDUAL SUBJECTS\n");
    
    }
    else if ((marks1 + marks2 + marks3)/3 <40){
        printf("YOU ARE FAILED IN EXAMINATION DUE TO LESS PERCENTAGE OVERALL");
    }
    else{
        printf("YOU ARE PASSED");
}
    return 0;
}


								PRACTICE SET 3
								QUESTION NO.2





#include<stdio.h>
int main(){

    int MATHS_MARKS;
    int PHYSICS_MARKS;
    int CHEMISTRY_MARKS;
    
    printf ("ENTER THE MARKS OF MATHS:\n");
    scanf("%d", &MATHS_MARKS);
    
    printf ("ENTER THE MARKS OF PHYSICS:\n");
    scanf("%d", &PHYSICS_MARKS);
    
    printf ("ENTER THE MARKS OF CHEMISTRY:\n");
    scanf("%d", &CHEMISTRY_MARKS);
    
    if (MATHS_MARKS >= 33){
        printf ("YOU HAVE PASSED IN MATHS\n");
    }
    else {
        printf ("YOU HAVE FAILED IN MATHS\n");
    }
    
    if (PHYSICS_MARKS >= 33){
        printf ("YOU HAVE PASSED IN PHYSICS\n");  
    }
    else {
        printf ("YOU HAVE FAILED IN PHYSICS\n");
    }
    
    if (CHEMISTRY_MARKS >= 33){
    printf ("YOU HAVE PASSED IN CHEMISTRY\n");  
    }
    else{
        printf ("YOU HAVE FAILED IN CHEMISTRY\n");
    }
    
    if (MATHS_MARKS+PHYSICS_MARKS+CHEMISTRY_MARKS/3 >= 40){
        printf("YOU HAVE PASSED IN THE EXAMINATION ");
    }
    else{
        printf("YOU HAVE FAILED IN THE EXAMINATION");
    }
    
    return 0;
}
    
									


										QUESTION NO.3




#include <stdio.h>

int main() {
    int income ;
    float tax;
    
    printf ("WRITE YOUR income");
    scanf ("%d",&income);
    
    if (income <250000){
    tax = 0;
    }

    else if (income > 250000&& income <=500000){
    tax = 0.05 * (income - 250000);
    }
    
    else if (income > 500000&& income <=1000000){
    tax = 0.05 * (500000 - 250000) + 0.2 * (income - 500000);
    }
    
    else{
     tax = 0.05 * (500000 - 250000) + 0.2 * (1000000 - 500000) + 0.3 * (income - 1000000);
    } 
    printf ("THE TOTAL TAX YOU NEED TO PAY IS %.2f", tax);
    
    return 0;
}




										QUESTION NO.4


#include<stdio.h>
int main(){
    
    int YEAR;
    printf ("ENTER YEAR:");
    scanf("%d",&YEAR);
    
    if (YEAR % 4 == 0 && (YEAR % 100 != 0) || YEAR % 400 == 0){
    printf ("THE ENTERED YEAR IS A LEAP YEAR");
    }
    else{
        printf ("THE ENTERED YEAR IS NOT A LEAP YEAR");
    }
    
    return 0;
} 



										QUESTION NO.5




//97 - 122
#include<stdio.h>
int main (){
    
    char CHARACTER;
    printf ("ENTER THE VALUE OR A CHARACTER:");
    scanf("%c",&CHARACTER);
    
    if (CHARACTER >= 97 && CHARACTER <=122){
    printf ("THE ENTERED CHARACTER IS LOWERCASE");
    }
    
    else{
    printf ("THE ENTERED CHARACTER IS NOT A LOWERCASE CHARACTER");
    }
    
    return 0;
}





										QUESTION NO.6



#include<stdio.h>
int main (){
    
    int A,B,C,D;
    printf("ENTER THE VALUE OF A\n");
    scanf("%d",&A);
    
    printf("ENTER THE VALUE OF B\n");
    scanf("%d",&B);
    
    printf("ENTER THE VALUE OF C\n");
    scanf("%d",&C);
    
    printf("ENTER THE VALUE OF D\n");
    scanf("%d",&D);
    
    if (A > B && A > C && A > D){
    printf ("A WHICH IS %d IS GREATER THAN B,C AND D",A);
    }
    else if (B > A && B > C && B > D){
    printf ("B WHICH IS %d IS GREATER THAN A,C AND D",B);
    }
    else if (C > A && C > B &&C > D){
    printf ("C WHICH IS %d IS GREATER THAN A,B AND D",C);
    }
    else if (D > A && D > B && D > C){
    printf ("D WHICH IS %d IS GREATER THAN A,B AND C",D);
    }
    
    return 0;    
}
 