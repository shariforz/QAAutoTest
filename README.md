Составить алгоритм: если введенное число больше 7, то вывести “Привет”

```csharp
using System;
					
public class Program
{
	public static void Main()
	{
		int num1;
    	Console.Write("\n\n");
   		Console.Write("Введите целое цифру : ");
   		num1= Convert.ToInt32(Console.ReadLine()); 
    	if (num1 < 7)
 		Console.WriteLine("Цифра меншьше 7\n");
    	else
 		Console.WriteLine("Привет\n");
	}
}
```

