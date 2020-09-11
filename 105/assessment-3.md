**How do you feel about the pace of the program so far? Is it too slow? Too fast? Or just right?**

 I believe the pace has been fine so far. Although we do not have our laptops yet, the amount of coding is fine and I have learned a lot. I am not picky when it comes to this stuff, I just assume you know what you are doing. I like the amount of synchronous and asynchronous classes as well.

**Why do you think functions are a useful tool to organize large programs?**

Functions are important to decrease the amount of repetition in our programs. There is no reason to type out something out many times when we can make just one function and call it many times. A large program will quickly become difficult to read without functions. It is useful to organize specific actions that will be used a lot, especially for something like a game, where things will need to be repeated thousands of times. A program created with no functions may work, but it will be less elegant.

**In class, we've been using the analogy of a zoo to explain scope. Describe the different types of scope using this analogy and provide examples using real JavaScript code.**

Scope is the reach that a specific variable has in a program. For instance, a variable created with `let` will not exist outside of the for loop it was created in. That variable can only be used in its local scope. A variable created outside of any braces is a global variable, and can be used anywhere. There are two types of local scoping rules, lexical and block. Lexical means that only functions create new scopes, and this only affects variables created with `var`. Block affects `let` and `const`, and it means that and curly braces will create new scopes. An example of scope in code is this:
```
let global = 15;
{
let local = 10;
}
console.log(global);
console.log(local);
``` 
The global variable is used with no problem, but the local variable gives an error due to block scoping. If the local variable were created with `var`, however, there would be no issue with printing it.
