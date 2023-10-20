# EXP-1 Java program to print the Arithmetic operations
## Aim:
To write java program to print the Arithmetic operations.

## Procedure:-
### Step 1:
Import the required packages.

### Step 2:
Get the input for arithmetic operations from the user.

### Step 3:
Perform arithmetic operations using the arithmetic operator.

### Step 4:
Display the result of the operations using print function.


### Step 5:
Stop the execution.

## Program:-
#### Developed By : Bharathi priyan T
#### Register Number : 212221040028

java program:
``
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num1,num2;
        System.out.print("Enter Two Numbers for Arithmetic Operations:");
        num1=sc.nextInt();
        num2=sc.nextInt();
        //Arithmetic Operations
        int sum=num1+num2;//Addition
        int diff=num1-num2;//Subtraction
        int prod=num1*num2;//Product
        int div=num1/num2;//Division
        int mod=num1%num2;//Modulus
        System.out.println("Sum of "+num1+" and "+num2+" = "+sum);
        System.out.println("Diffrence of "+num1+" and "+num2+" = "+diff);
        System.out.println("Product of "+num1+" and "+num2+" = "+prod);
        System.out.println("Division of "+num1+" and "+num2+" = "+div);
        System.out.println("Modulus of "+num1+" and "+num2+" = "+mod);
    }
}
``
## Output:-

![238122570-27d459bb-54b2-4716-b992-ab8691043310](https://github.com/SarankumarJ/Java-Ex-01/assets/94778101/03c76619-d06a-46df-a49f-7572723a3ee9)

## Result:-

A java program to print the Arithmetic operations has been executed Successfully.
