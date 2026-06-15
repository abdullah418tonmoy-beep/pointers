
#include<stdio.h>
int main()
{
    int x, *pc;//* diya pointors create kori
    x=8;
    printf("Value: %d\n",x);
    printf("Address: %p\n",&x);

    pc= &x;// & for address

     printf("Value: %d\n",*pc);
    printf("Address: %p\n",pc);

    *pc=2; //* for value
    
     printf("Value: %d\n",x);
    printf("Address: %p\n",pc);

return 0;
}


