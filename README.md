#include <stdio.h>
int main ( ) 
{char c1,c2;
  scanf("%c",&c1);
  if(c1>='A'&&c1<='Z')
  {
  	c2=c1+32;
  	printf("%c,%c\n",c1,c2);}
  else
  if(c1>='a'&&c2<='z')
  {
  	c2=c1-32;
  printf("%c,%c\n",c1,c2);}
  else
  printf("error");
}
