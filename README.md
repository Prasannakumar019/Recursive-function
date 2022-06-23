## EX NO:07
## DATE:18.5.22
# <p align="center">Recursive-function

## Aim:
To write a C# program to reverse a number using recursive function.

## Algorithm:
## Step1:
Create a function for reversing.

## Step2:
Get the number from the user.

## Step3:
In the function find reminder of the number and multiply it by 10 and add the reverse number.

## Step4:
Recusively call this function to get the reversed number.

## Step5:
print the reversed number.
## Program:
```python
using System;
class example
{
    public static void fun(int n)
    {
        if(n < 1)
        {
            
            return;
        }
        else
        {
            Console.Write(n % 10);
            fun(n / 10);
        }
    }
    public static void Main()
    {
        int i;
        i = Convert.ToInt32(Console.ReadLine());
        fun(123);
        
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/75235090/170515577-ff0a8b88-0353-4c90-b783-1fbf5235d42a.png)

## Result:
Thus C# program to reverse a number using recursive function is written and executed sucessfully.
