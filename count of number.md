//  数一个整数的位数
#include <stdio.h>

int main(){
  int x;
  int n = 0;
  
  scanf("%d",&x);
  n++;
  x /= 10;
  
  while (x){
  	n++;
  	x /= 10;
  }
  printf("%d\n",n);
}
