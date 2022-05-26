# Recursive-function

## Aim:
To write a C# program to reverse a number using recursive function.

## Algorithm:

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
