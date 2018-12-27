# C# != Operator Tutorial

This C# != Operator Tutorial
www.amiedd.com AmieDD - code, cosplay and games

```C# runnable

using System;

class InequalityTest
{
    static void Main()
    {
        // Numeric numbers that don't equal:
        Console.WriteLine((2 + 2) != 4);

        // Reference equality, two objects, same value
        object s = 1;
        object t = 1;
        Console.WriteLine(s != t);

        // Strings, same string objects
        string a = "howdy";
        string b = "howdy";

        // compare string values
        Console.WriteLine(a != b);

        // compare string references
        Console.WriteLine((object)a != (object)b);
    }
}
/*
Output:
False
True
False
False
*/
```

# About C# != Operators

!= Not equal.Predefined value types, the inequality operator (!=) returns true if the values are different, false. If the reference types isn't a string, != returns true if its two operands points to different objects. String type, != compares the values of the strings.


