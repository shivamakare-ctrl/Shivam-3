# Shivam-3
C language 
#include<stdio.h>
void main()
{
  float uv_index;
  printf("enter UV Index:");
  scanf("%f",&uv_index);
  if (uv_index>=0 && uv_index<=2)
  {
   printf("UV Risk:Low");
  }
  else if (uv_index>2 && uv_index<=5)
  {
   printf("UV Risk:Moderate");
  }
  else if (uv_index>5 && uv_index<=7)
  {
   printf("UV Risk:High");
  }
  else if (uv_index>7 && uv_index<=10)
  {
   printf("UV Risk:Extreme");
  }
  else
  {
   printf("Invalid UV Index");
  }
  getch();
}



