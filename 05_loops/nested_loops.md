05_loops/nested_loops.md
br
## 1. Concept in Your Own Words.
<br>
For and while loops are both used to repeat code, but they are used in different situations. A for loop is usually used when we know how many times we want to repeat something. A while loop is used when we don’t know how many times the loop will run, and it depends on a condition. In a for loop, everything is written in one line: initialization, condition, and update. In a while loop, these parts are written separately. The execution checks the condition first before running the loop. Both loops stop when the condition becomes false.

## 2. Key C# Syntax
```csharp

// for loop
for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}

// while loop
int j = 0;
while (j < 5)
{
    Console.WriteLine(j);
    j++;
}
