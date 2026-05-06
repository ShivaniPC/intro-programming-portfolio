08_function.md
<br>
Function (Method): A reusable block of code that performs a specific task when it is called
Function = a named block of code you can run anytime.
When a function is called, the program jumps to that function, runs the code inside it, and then returns back to where it was called. Functions can also take inputs called parameters, 
which allow them to work with different values each time. Some functions return a value,
<br>
2. Key C# Syntax
<br>
 void Greet()
{
    Console.WriteLine("Hello!");
}

 void Main(string[] args)
{
    Greet(); // function call
}
<br>
3. Eureka Exercise / Moment
<br>
At first, I didn’t understand why my function wasn’t running even though I wrote it correctly.
I forgot that a function only runs when it is called. I thought just writing it was enough.
<BR>
4. Common Beginner Mistake
<BR>
A common mistake is forgetting to call the function after creating it.
This happens because beginners think defining the function automatically runs it, but it only runs when explicitly called.
