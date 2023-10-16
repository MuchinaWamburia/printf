0X11. C - PRINTF

The printf function in C is used to print formatted output to the standard output (usually the console or terminal). It allows you to format and display different types of data.
Here's a simple example of how to use the printf function:
#include <stdio.h>

int main() {
    int number = 42;
    double pi = 3.14159;
    char letter = 'A';
    char name[] = "John";

    printf("Integer: %d\n", number);
    printf("Double: %f\n", pi);
    printf("Character: %c\n", letter);
    printf("String: %s\n", name);

    return 0;
}
When you run this code, it will display:
Integer: 42
Double: 3.141590
Character: A
String: John

The %d, %f, %c, and %s in the format string are called format specifiers. They are placeholders that printf uses to know where to insert the values of the variables. Each specifier corresponds to a specific data type.
Include the <stdio.h> header at the beginning of your program to use the printf function.
