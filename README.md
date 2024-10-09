#include <stdio.h>

int main() {
    int rollno;
    float per;

    printf("Enter the rollno and percentage: ");
    scanf("%d %f", &rollno, &per);

    printf("Rollno is = %d and percentage is = %.2f\n", rollno, per);

    return 0;
}
