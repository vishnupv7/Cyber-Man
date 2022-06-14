#include <stdio.h>

int main()
{
    int i,j,k;
    int a[20];
    int size;
    int position;
    printf("enter the size of the array :");
    scanf("%d",&size);
    printf("enter the values of the array");
    for(i=0;i<size;i++)
    {
        
        scanf("%d",&a[i]);
    }
    printf("enter the position of the elemt to delete :");
    scanf("%d",&position);
    for(i=0;i<size;i++)
    {
        if(i==position)
        {
            for(j=i;j<size;j++)
            {
                a[j]=a[j+1];
            }
            size--;
        }}
       for(i=0;i<size;i++)
       
      {
          printf("%d",a[i]);      
          
      }
        
    
    return 0;
}
