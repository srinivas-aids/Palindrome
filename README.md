# <p align="center">Palindrome</p>
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step 1:
Create a new Class named palindrom.
### Step 2:
Declare three variables of string data type.
1. input - Store the input from user.
2. str - Convert user input to lower case and store it.
3. pal - Reverse the string str and store it.
### Step 3:
Get input from the user and store it. Then convert it to lower case.
### Step 4:
Using for loop, iterate through the each character from the end to begining and add it to the new variable called pal
### Step 5:
Using If-else statement check whether the input string & reversed string are same.
### Step 6:
Print the input and reversed string along with the whether palindrom or not.
### Step 7:
End of the Program.
## Program:
## Developed By: SRINIVAS.u
## Register No: 212221230108
```C#
using System;
class HelloWorld
{
    static void Main()
    {
        string num1, rem, rev = "";
        num1 = Console.ReadLine();
        rem = num1;
        for (int s = num1.Length - 1; s >= 0; s--)
        {
            rev += num1[s];
        }
        Console.WriteLine(rev);
        if (rev == rem)
            Console.WriteLine(rem + ":is a palindrome");
        else
            Console.WriteLine(rem + ":is not a palindrome");

    }
}
```
## Output:
<img width="867" alt="image" src="https://github.com/srinivas-aids/Palindrome/assets/93427183/23b9577d-4777-42de-960e-fe4e3500ec2c">

<img width="867" alt="image" src="https://github.com/srinivas-aids/Palindrome/assets/93427183/bd5ee11b-68c5-4652-89fc-cc0d11179ab5">


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
