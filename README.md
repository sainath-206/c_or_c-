# c_or_c-
test c and c++
#include<stdio.h>
main{
int *ptr,n,i;
printf("expected size for malloc\n");
scanf("%d",n);
ptr=(int*)malloc(n*sizeof(int))

if(ptr==NULL)
{
  printf("memory is not allocated");
}
}
// add members 

for(i=0;i<n;++i)
{
  ptr[i]=i+1;
}
