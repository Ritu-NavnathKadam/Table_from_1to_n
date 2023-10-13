# Table_from_1to_n
#include <stdio.h>

int main() 
{
    int i, j,n;
    printf("Enter any number ");
    scanf("%d",&n);
    for (i = 1; i <= n; i++)
    {
        printf("Multiplication table for %d:\n", i);
        for (j = 1; j <= 10; j++)
        {
            printf("%d x %d = %d\n", i, j, i * j);
        }
        printf("\n"); // Separate each table with a blank line
    }

    return 0;
}
