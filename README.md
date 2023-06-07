# Ex-7-Write-a-java-program-to-insert-an-element-into-array

## AIM:
To write a java program to insert an element into array.

## ALGORITHM: 
### Step 1:
Import the necessary packages.
### Step 2: 
Get the elements values in array from the user.
### Step 3: 
Get the position value and the element value that is to be inserted in the array.
### Step 4: 
Insert the element into the array.
### Step 5:  
Print the result.
### Step 6: 
End the program.
## PROGRAM:
~~~
Name   : H.Syed Abdul Wasih
Reg No : 212221240057
~~~
~~~
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        int n, pos, x;
        Scanner s = new Scanner(System.in);
        System.out.print("Enter no. of elements you want in array: ");
        n = s.nextInt();
        int a[] = new int[n+1];
        System.out.println("Enter all the elements: ");
        for(int i = 0; i < n; i++)
        {
            a[i] = s.nextInt();
        }
        System.out.print("Enter the position where you want to insert element: ");
        pos = s.nextInt();
        System.out.print("Enter the element you want to insert: ");
        x = s.nextInt();
        for(int i = (n-1); i >= (pos-1); i--)
        {
            a[i+1] = a[i];
        }
        a[pos-1] = x;
        System.out.print("After inserting:  ");
        for(int i = 0; i < n; i++)
        {
            System.out.print(a[i]+",");
        }
        System.out.print(a[n]);
    }
}

~~~

## OUTPUT:

![exp7](https://github.com/abdulwasih2003/Ex-7-Write-a-java-program-to-insert-an-element-into-array/assets/91781810/48c6d415-7641-466e-849e-ecd160db67e0)

## RESULT:
Thus the java program to insert an element into array is successful.



