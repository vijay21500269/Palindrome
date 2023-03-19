# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## step1:
Import the 'system' namespace to use the classes present in the 'system' namespace.

## step2:
Declare the main method.
## step3:
Declare name variable in the string format.
## step4:
And declare an empty string to reverse the string input.

## step5:
Using for loop reverse the input string and store it in rev.

## step6:
Using if else loop check whether the input string and the reversed string are same.

## step7:
Print the result.






## Program:
~~~
using System;
namespace palindrome
{
    public class Program
    {
        static void Main(string[] args)
        {
            string str1;
            string rev = "";
            Console.Write("Enter a string : ");
            str1 = Convert.ToString(Console.ReadLine());


            for (int i = str1.Length - 1; i >= 0; i--)
            {
                rev += str1[i];
            }

            if (str1 == rev)
            {
                Console.WriteLine("{0} is Palindrome.", str1);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", str1);
            }
        }
    }
}
~~~

## Output:
![c#1](https://user-images.githubusercontent.com/94381788/226185169-1911d3c9-7033-447b-a4e1-44becd37ae9b.png)
![c#2](https://user-images.githubusercontent.com/94381788/226185190-9d623b0d-c7de-453e-9d03-a489f96b93cd.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
