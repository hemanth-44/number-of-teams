#include<stdio.h>
#include<conio.h>
Void rank(int n, introduction r[]);
Void main()
{
Int i, n, r[10],t=0;
Printf("enter no of soldiers ");
Scanf("%d",&n);
For(i=0;i<n;i++)
{
Scanf("%d",&r[i]);
}
Rank();
}
Void rank(int n ,int [])
{
For(i=0;i<n;i++)
{
For(j=1;j<=n;j++)
{
Printf("%d",r[i]);
If(r[i]<r[j]||r[i]>r[j])
Printf("%d",r[j]);
}
}
T++;
Printf("no of teams:%d",t); 
}
