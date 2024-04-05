# Code structure
The first thing we’ll learn is the building blocks of code.

## Statements
Statements are syntax constructs and commands that perform actions.
We’ve already seen a statement, alert('Hello, world!'), which shows the message “Hello, world!”.
We can have as many statements in our code as we want. Statements can be separated with a semicolon.
For example, here we split “Hello World” into two alerts:
```
alert('Hello'); alert('World');
```
Usually, statements are written on separate lines to make the code more readable:
```
alert('Hello');
alert('World');
```
## Semicolons
A semicolon may be omitted in most cases when a line break exists.
This would also work:
```
alert('Hello')
alert('World')
```
Here, JavaScript interprets the line break as an “implicit” semicolon. This is called an automatic semicolon insertion.
In most cases, a newline implies a semicolon. But “in most cases” does not mean “always”!
There are cases when a newline does not mean a semicolon. For example:
```
alert(3 +
1
+ 2);
```
