04_switch.md
<br>
Switch statement: A control structure that checks a variable against multiple 
possible values and runs the matching case.
<br>
2. Key C# Syntax
<br>
int day = 2;

switch (day) // expression
{
    case 1:
        Console.WriteLine("Monday");
        break;
    case 2:
        Console.WriteLine("Tuesday");
        break;
    default:
        Console.WriteLine("Other day");
        break;
}
<br>
switch = checks a value
case = possible match
break = stops the switch
default = runs if no match
<br>
firstly ididnot understand how this work .
but when i used this with an example and assignments .i undrstood well.
<br>
4. Common Beginner Mistake

A common mistake is forgetting the break statement. This happens because beginners think the switch will stop on its own,
but without break, it continues into the next case.
