# it-s-my-first-repository
#include <stdio.h>
#include<string.h>
int main()
{
    char str1[100],str2[100],i,j,count=0,len;
    printf("Enter the first strings:");
    scanf("%s",str1);
    printf("enter the second string:");
    scanf("%s",str2);
    printf("output is:");
    len=strlen(str1);
    for(i=0;str1[i]!='\0';i++)
    {
        for(j=0;str2[j]!='\0';j++)
        {
            if(str2[j]==str1[i])
            count++;
            
        }
    }
    if(len==count)
    printf("Anagram");
    else
    printf("Not a Anagram");
    return 0;
}
