# -p4a.c
C Program to check positive number
#include <stdio.h>
int main () {
  int a;
  printf("enter number to check positivity ");
  scanf("%d",&a);
  if (a>0)
  printf ("given number%d is positive" ,a);
  return 0 ;
}
