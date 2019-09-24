# Collection of notes in the C language 

Scratch: Say(hello, world)

```C
printf("hell0, world/n");
```

All printed words are called strings and strings are enclosed by "string" <br>
/n tells computer to start a new line (enter) <br>
The ; is like the period at the end of a sentence. It tells the computer that this is the end of the statement. 

Scratch: Set counter to 0 

```C
int counter=0;
```

In C, you must declare the type of varibale you are creating 

Scratch: Change counter by 1

```C 
counter = counter + 1; # will add any number to counter 
counter + = 1; # will add any number to counter
counter + +; # only adds plus one to counter
```

single = doesn't mean "equals", it means "assign" or "get." <br>
Don't need to repeat int since you already told the computer, don't need to repeat yourself 

Scratch: If x is less than y say "x is less than y" 

```C
if (x < y) 
{
printf("x is les than y"/n);
}
```

Curly braces seperate the statements 

Scratch: If x is less than y say "x is less than y" else say "x is not less than y" 

```C
if (x < y) 
{
printf("x is les than y"/n);
}
else
{
printf("x is not less than y"/n); 
}
```

You want your code to be readable, why we add in enters, far simpler to understand
