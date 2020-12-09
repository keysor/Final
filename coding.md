# **Ben Dargue, Final Project**
[Home](https://github.com/keysor/Final/blob/main/README.md)   
## Directory 
[About](https://github.com/keysor/Final/blob/main/about.md)  [Coding](https://github.com/keysor/Final/blob/main/coding.md)  [Hobbies](https://github.com/keysor/Final/blob/main/hobbies.md)  [Fun Facts](https://github.com/keysor/Final/blob/main/funfacts.md)
# Coding
**Here is one of my codes I produced in C**
``` #include <stdio.h>

int main (void)
{
    int A;
    int B;
    int C;
    int D;
    int sum;
    int result;
    int product;
    int remain;
    int quotient;

    int times;
    int quantity;

    printf("Enter integer A\n");
    scanf("%d", &A);

    printf("Enter integer B\n");
    scanf("%d", &B);

    printf("Enter integer C\n");
    scanf("%d", &C);

    printf("Enter integer D\n");
    scanf("%d", &D);

    sum = A + B;
    quotient = B / C;
    product = C * D;
    remain = B % C;

    times = A * B;
    quantity = C + D;
    result = times / quantity;

    printf("A = %d\n", A);
    printf("B = %d\n", B);
    printf("C = %d\n", C);
    printf("D = %d\n", D);

    printf("The sum of A and B = %d\n", sum);
    printf("The integer quotient of B divided by C = %d\n", quotient);
    printf("The product of C and D = %d\n", product);
    printf("The integer remainder of B divided by C = %d\n", remain);
    printf("The product of A and B divided by the quantity sum of C and D = %d\n", result);

    return 0;
    }

```
This code takes four numbers that you input of your free will and lists some outputs (which were required for the code in the class).
It takes the first number you input as A, the second as B, the third as C and the fourth number you input as D it then gives you the sum of the **A and B number you input**. **The integer quotient of B divided by C.**
**The product of C and D.** **The integer remainder of B divided by C** and the product of **A and B divided by the quantity sum of C and D;** It then displays which is which and displays the number outputted in a clean format for the user to read and then kills the program allowing you to run it again and test different numbers if you desire.
