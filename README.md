# Assignment-binary-searching
Binary Searching
#include <stdio.h>
#include <math.h>
int main()
{
int c, first, last, m,t, array[]={7,9,11,13,23,27,33,37,41,47,53,57};
int n=12;
int l=0;
int r=n-1;
printf ("r=%d",r);
while(l<=r)
{
   m=floor((l+r)/2);
   printf("\n m=%d",m);
    break;
}

printf ("\nEnter Target to Search");
scanf ("%d",&t);
    if (array[m]<t)
{
        l = m+1;
        printf("l=%d",l);
}
      else if(array[m]>t)
        {r = m-1;
        printf("\nr=%d",r);
}
else 
{
	return m;
	printf("\n Return Unsuccessful");
}
}
out put
r=4
or 
l=6
