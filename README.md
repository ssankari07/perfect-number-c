#include<stdio.h>
int main()
{
    int n, rem, sum = 0, i;
 
    printf("Enter a Number\n");
    scanf("%d", &n);
    for (i = 1; i <= n-1; i++)
    {
        rem = n % i;
	if (rem == 0)
        {
            sum = sum + i;
        }
    }
    if (sum == n)
        printf("Entered Number is perfect number");
    else
        printf("Entered Number is not a perfect number");
    return 0;


}
output:
4
not a perfect number
