include <stdio.h>

int main()
{ 
    int rollno [5];
    int i;
    printf("enter the value in array");
    for(i=0;i<=4;i++)
    {
        scanf("%d",&rollno[i]);
    }
    for(i=0;i<=4;i++)
{
    printf("%d",rollno[i]);
}
    return 0;
}
