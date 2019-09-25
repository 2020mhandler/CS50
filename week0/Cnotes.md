# Notes in the C language

Scratch Say(hello, world)

```C
printf("hello, world\n"); //use double forward slash to comment code
```

All printed words are called strings and strings are enclosed by "string" <br>
\n tells computer to start a new line <br>
The ; is like the period at the end of a sentence. It tells the computer to stop the current line of code <br>
Scratch: set counter to 0

```C
int counter = 0;
```

In C you must declare the type of variable you are creating <br>
Scratch: Change counter by 1

```C
counter = counter + 1;
```

```C
if(x < y) 
{
  printf("x is less than y");
}
```

```C
if(x < y)
{
  printf("x is less than y\n");
}
else if (x > y)
{
  printf("x is greater than y \n");
}
else if (x == y)
{
  printf("x is equal to y\n");
}
```

Double equals sign means equal to in C while single equals sign means set to

```C
while(true) //true has the value of always being true so it can be used to create a forever loop
{
  printf("hello, world\n");
}
for(int i = 0; i < 50; i++) { //set variable, number of repetitions, and incrementation
  printf("hello, world\n");
}
```

A return value is the output of a program

```C
  string answer = get_string("What's your name?\n");
  printf("%s", answer); //% symbol indicates a certain format. In this case it tells the printf function to print a string
```
```C
#include <stdio.h>
int main(void) 
{
  printf("hello,world\n");
}
```
