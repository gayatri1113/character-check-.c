//# character-check-.c//
#include<stdio.h>
int main()
{
    char ch;
    printf("Enter character:");
    scanf("%c",&ch);
    if(ch>=65 && ch<=90)
    {
        printf("it is a capital letter");
    }
    else
    {
        if(ch>=97 && ch<=122)
        {
            printf("it is a small character");
        }
        else
        {
            if(ch>=48 && ch<=57)
            {
                printf("it is a digit");
            }
            else
            {
                printf("it is a special character");
            }
        }
    }
    return 0;
}
