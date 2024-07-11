#include <stdio.h>

int main() {
    int N, count = 0;

    printf("Enter the value of N: ");
    scanf("%d", &N);

    for (int A = 1; A <= 500; A++) {
        for (int B = 1; B <= A; B++) {
            if ((A * A - B * B) == N) {
                count++;
                printf("A = %d, B = %d\n", A, B);
            }
        }
    }

    printf("Number of pairs: %d\n", count);

    return 0;
}
