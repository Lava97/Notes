# Understanding Errors in PHP
## This file will go through the types of errors that exist in PHP and understanding them.

An error is a type of mistake. In PHP if we encounter an error or warning an error message with the filename, line number and a message describing the error is sent to the browser.  
It is very important to understand the errors in order to be able to solve the problems faster, or actually to not even commit those errors.

### Types of errors:
1. Parse Errors(syntax errors)  
This type of error occurs if there is a syntax mistake in the script. This error will stop the execution of the script.  
There are many reasons that can cause for this error to occur.  
The common reasons are as follows:  
    * Unclosed quotes.  
    * Unclosed braces.  
    * Missing semicolon.  
    * Missing or extra parenthesis.
    
2. Fatal Errors  
This type of error is caused when PHP understands what you have written(meaning no syntax errors), however what you are asking it to do, can't be done.  
This error will stop the execution of the script.
For example:  
```
<?php
function func1(){
  echo "Hello World!";
}
func2();
?>
```

3. Warning Errors  
Main reasons for these type of errors are, for example to include a missing file or use incorrect number of parameters in a function.  
This error will not stop the execution of the script.

4. Notice Errors  
Notice, that the error occurs, when you try to access a undefined variable, then it produces a notice error.  
For example:  
```
<?php
$a = "World";
echo $b;
?>
```
