# it-s-my-first-r #include <stdio.h>

int main()
{
    int i,j;
   for(i=6;i>=1;i--)
   {
       for(j=6;j>=i;j--)
       {
           printf("%d ",j);
       }
       printf("\n");
   }
    return 0;
} 
