# lesson-2

## Types, Variables, and Operations
```c
char a; // a single byte, capable of holding one character
int i; // an integer; max is based on machine
float f; // single-precision floating point number
double d; // double-precision floating point number
short int si; // decreases the size of an int; int can be omitted
long int li; // increase the size of an int; int can be omitted
```

VARIABLES - RESTRICTIONS
  - Begins with a letter
  - Consists of letters and numbers
  - The underscore "_" counts as a letter
  - Case sensitive
  - Use lower case for variable names & all caps for constants
  - Cannot use reserved keywords
  - ** Reccomended: When giving variable names, please provide good variable names.
  
CONSTANTS
  - Numbers are constants
```c
int a = 1234; // no suffix
long l = 123456789L; // suffix of l or L
// An integer constant too big to fit into an int will also be taken as a long. 

unsigned long ul = 123456789U; // suffix of u, U → unsigned constant; ul, UL → unsigned long
double d = 1.234; // number with decimal is default a double
float f = 1.234f; // suffix of f or F needed to indicate that it is not a double
long double ld = 1.234l; // suffix of l or L

// the value of an integer can be specified in octal or hexadecimal instead of decimal.
int octal = 037; // leading 0 on an integer means octal, so this is decimal 31
int hex = 0x1f // leading 0x or 0X means hexadecimal, so this is decimal 31
// octal and hexadecimal constants may also be followed by L to make them long and U to make // them unsigned:0XFUL is an unsigned long constant with value 15 decimal.
```
A character constant is an integer, written as one character within single quotes such as ‘x’. The value of a character constant is the numeric value of the character in the machine’s character set.
```c
int val = 'c';
char tab = '\t';
```

Certain characters can be represented in character and string constants by escape sequences like \n (newline); these sequences look like two characters, but represent only one.

![alt text](Escape_Sequences.png)
***** Note for characters you must use single quotes. 


![alt text](ASCII_ConversionChart.png)
