include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y;
        scanf("%d%d",&x,&y);
    if(x>y)
    {
        printf("Did not perform well");
    }
    else if(y>x)
    {
        printf("Performed well");
    }
else 
{
    printf("Did not participate");
}
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
