#include <stdio.h>

int main(void)
{
    int A[3] = {1,2,3};
    int B[10];
    int i;
    
    for (i = 0; i < 10; i++)
    {
        B[i] = A[i % 3];
    }
    
}
