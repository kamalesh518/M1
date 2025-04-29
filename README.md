
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include<stdio.h>
int main(){
    float a,b;
    scanf("%f%f",&a,&b);
    float dis=a*b;
    printf("distance:%.2f km",dis);
}
```
## OUTPUT:


![Screenshot 2025-04-29 095656](https://github.com/user-attachments/assets/6b1ca883-8a76-4a91-87ee-cf0a85192602)















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>

int main() {
    int A;

    // Prompt user to enter a value
    printf("Enter a number (A): ");
    scanf("%d", &A);

    // Check if A is positive
    if (A > 0) {
        printf("A is a positive number.\n");
    } else if (A < 0) {
        printf("A is a negative number.\n");
    } else {
        printf("A is zero.\n");
    }

    return 0;
}
```
# OUTPUT:

![Screenshot 2025-04-29 100400](https://github.com/user-attachments/assets/1252ad4c-6656-4c73-a279-d2ecbbd1e413)










# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>
int main(){
    int a,b,c,d,e,f;
    scanf("%d%d%d%d%d%d",&a,&b,&c,&d,&e,&f);
    float total=a+b+c+d+e+f;
    float avg=total/6;
    printf("Total marks = %.2f\n",total);
    printf("Average marks = %.2f\n",avg);
    printf("Percentage = %.2f",avg);
    
}
```
## OUTPUT:
![Screenshot 2025-04-29 100508](https://github.com/user-attachments/assets/c97443ae-3012-4aef-9c93-b2b936725da8)









## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a>=70)
    printf("A+ GRADE");
    else if ((a>=60)&& (a<70))
    printf("A GRADE");
    else if ((a>=50)&& (a<60))
    printf("B GRADE");
    else if ((a>=40)&& (a<50))
    printf("C GRADE");
    else
    printf("F GRADE");
    return 0;
}
```
## OUTPUT:


![Screenshot 2025-04-29 100602](https://github.com/user-attachments/assets/330cef61-87a6-4e60-a533-c9dce0b3d9b8)







	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include<stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    if ((a%2!=0)&&(a>=25))
          printf("The number is odd\nThe number is greater than or equal to 25");
    else
       printf("The number is NOT an odd number");
}
```
## OUTPUT:
![Screenshot 2025-04-29 100657](https://github.com/user-attachments/assets/ce91c5de-cacd-40e8-8c5d-96f0cc2ea4f1)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

