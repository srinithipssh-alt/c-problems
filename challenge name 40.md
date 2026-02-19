#include <stdio.h>

int main()
{ int i,n,voltage;
int min,low=0;
scanf("%d",&n);
for(i=0;i<n;i++){
    scanf("%d",&voltage);
    if(i==0){
        min=voltage;
        if(voltage<min){
            min=voltage;
            if(voltage<210){
                low++;
            }
        }
    }
}

printf("minimum voltage:%d\n",min);
printf("low voltage events:%d",low);
return 0;
}