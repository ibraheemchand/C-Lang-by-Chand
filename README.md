# C-Lang-by-Chand
My First C language Repository
Auther--Ibraheem Chand


#include <stdio.h>
int main(){
  int marks1 , marks2 , marks3 ;
  printf("Enter marks1\n"); 
  scanf("%d", &marks1);
  printf("Enter marks2\n"); 
  scanf("%d", &marks2);
  printf("Enter marks3\n"); 
  scanf("%d", &marks3);

  if (marks1<33 || marks2<33 || marks3<33)
  {
    printf("You are failed : Due to Less marks in individual subject (S)\n");
  }
  else if ((marks1+marks2+marks3)/3<33)
  {
    printf("You are failed : Due to Less marks in All subjects\n");
  }
  else printf("You are passed");
  
    return 0 ;
}
