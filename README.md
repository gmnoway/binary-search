# binary-search
İkili Arama C Kodu (Binary Search)

#include <stdio.h>
#include <math.h>
int main()
{
     int a[i]={2,3,7,9,10,11,17,20,32,60};
     int m, konum, n=9, x=20;
     int i=0;
     int j=n;

     while(i<j)
     {
             m=floor((i+j)/2);
             if(x>a[m])
             i=m+1;
             else
             j=m;
             printf(" i=%d , j=%d, m=%d "i,j,m);
     }
     if(x==a[i]) 
     konum=i;
     else
     konum=-1;
     
     printf("%d",location);
