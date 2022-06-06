# Sum-of-Digits-of-a-Five-Digit-Number
My first repository
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
	
    int n,digit,temp,sum=0;
    scanf("%d", &n);
    temp = n;
while(temp > 0)
{
    digit = temp % 10;
    sum = sum + digit;
    temp = temp / 10;
}
printf("%d\n",sum);
    return 0;
}
