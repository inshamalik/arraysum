#include<stdio.h>
int main()
  {
  int arr[] ={2,4,6,8};
  int size =sizeof arr/sizeof arr[0];
  int total =0;
  printf("the sizeof arr is %lu & the size of arr[0] =%lu\n",sizeof arr,sizeof arr[0]); 
    for(int i=0;i<size;i++)
    {
        total=total + arr[i];
    }
    printf("the sum of array =%d\n",total);
  }
