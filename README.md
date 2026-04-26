#include <stdio.h>

int main() {
    int num;

    printf("Enter a number: ");
    scanf("%d", &num);

    if (num % 2 == 0) {
        printf("The number is odd = 0\n");
        printf("The number is even = 1\n");
    } else {
        printf("The number is odd = 1\n");
        printf("The number is even = 0\n");
    }

    return 0;
}
