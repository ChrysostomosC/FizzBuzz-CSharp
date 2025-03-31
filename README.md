# FizzBuzz in C# 🎉

## Description  
This is a simple console application written in C# that prints numbers from **1 to 100**, replacing:  
✅ Numbers divisible by **3** with `"Fizz"`  
✅ Numbers divisible by **5** with `"Buzz"`  
✅ Numbers divisible by **both 3 and 5** with `"FizzBuzz"`  

This project is a classic programming exercise that helps in understanding loops, conditionals, and modular arithmetic in C#.  

## 💻 How It Works  
The program iterates through numbers **1 to 100** and applies the following rules:  

```csharp
for (int i = 1; i <= 100; i++)
{
    if (i % 3 == 0 && i % 5 == 0)
        Console.WriteLine("FizzBuzz");
    else if (i % 3 == 0)
        Console.WriteLine("Fizz");
    else if (i % 5 == 0)
        Console.WriteLine("Buzz");
    else
        Console.WriteLine(i);
}

## <hr />
![Screenshot 2025-03-27 163852](https://github.com/user-attachments/assets/6341b4cd-1a12-43d4-912b-d897ee362498)<hr />
![Screenshot 2025-03-27 163913](https://github.com/user-attachments/assets/9925da8f-8d49-4dec-99b4-e33643c56199)<hr />

