# Print-Inverted-Triangle-of-Stars
Using C language program is made which gives the output to Print Inverted Triangle of Stars
#include <stdio.h>
int main() {
    int n, i = n, j;
    scanf("%d", &n);
    while(i > 0) {
        j = 1;
        while(j <= i) {
            printf("* ");
            j++;
        }
        printf("\n");
        i--;
    }
    return 0;
}
