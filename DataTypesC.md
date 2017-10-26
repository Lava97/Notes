# Data Types in C Programming Language
## Data Types
C supports several different types of data. Each are represented differently within a computer's memory. I will be listing the basic data types and their memory requierments.

Please note that memory requierments may vary for each data type, depending on which C compiler is used. Here I will be taking in consideration **GCC(GNU Compiler Collection), which is the standard(ANSI) C Compiler**.

### Basic Data Types:
1. int
   
   Represents integer quantity.  
   Memory Requirement : 2 Bytes.
   
2. char
   
   Represents single character.  
   Memory Requirement : 1 Byte.
   
3. float
   
   Represents floating-point number. Basically a number containing a decimal point and/or an exponent.  
   Memory Requirement : 4 Bytes(1 word).
   
4. double
   
   Represents double-precision floating-point number.   
   Memory Requirement : 8 Bytes(2 words).
   
## Data Type Modifiers/Qualifiers
These basic data types can be augmented by using **data type modifiers/qualifiers**.  
These are: *short*, *long*, *signed* and *unsigned*.

Usually an integer is by default *signed*. That means, the integer values can be negative. So, **short int** or **int** both being 2 bytes, the values can range from -32,768 to +32,767.  
Then we move on to **long int**, usually **long** would be double of **short**. So, **long int** will be 4 bytes.  
In a normal int/short int or long int, the left most bit is used for the sign. If we were to have **unsigned int**, all the bits are used to represent the numerical value. So, **unsigned int** will have values ranging from 0 to 65,535.  
We can also use *unsigned* like this, for example: **unsigned short int** or **unsigned long int**.

We can also have long double, which may refer to a "extra-large" double-precision type requiring more than 2 words of memory, usually 10 bytes.

<br><br><br><br><br><br>
The information found in this document is heavily based off a book, Programming in C, written by Byron S. Gottfried.
