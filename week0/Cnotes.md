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
## IDE Notes
To run a program either clang file or ./file <br>
To save code in a file write -o filename <br>
make to make new file <br>
mkdir to make directory <br>
cd ~/ to change directory <br>
get_string prompts the user for a string <br>
rm to delete file <br>
touch to create file <br>
get_int prompts user for an integer <br>
numbers with decimal points are called floats <br>

```C
  #include <cs50.h>
  #include <stdio.h>
  string name = "george";
  printf("hello, %s\n", name); //write %, variable type, and later write variable name to insert variable
```
After a % type in .(integer)f to specify the number of decimal places <br>
|| (double lines mean or) <br>
&& (double and sign means and) <br>
!= means not equal to <br>
```C
  for(int i = 0; i < 3; i++) {
    printf("cough\n");
  }
```
Final unit project commands <br>
help50

style50

check50

submit50
