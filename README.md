#include<stdio.h>
int main(){
int n,i,j,s;
printf("enter the size of the matrix :");
scanf("%d",&n);
for(i=1;i<=n;i++){
    for(s=i;s<=n-1;s++){
        printf(" ");
    }
    int num=1;
    for(j=0;j<=i;j++){
        printf("%d ", num);
        num=num* (i-j)/(j+1);
    }
  printf("\n");
}
return 0;
}
