**#include <stdio.h>**



**int main()**

**{ int i,n,errors;**

**int total=0,critical=0;**

**scanf("%d",\&n);**

**for(i=0;i<n;i++){**

    **scanf("%d",\&errors);**

    **total=total+errors;**

    **if(errors>50){**

        **critical++;**

    **}**

    **}**

**printf("total errors:%d\\n",total);**

**printf("critical hours:%d",critical);**

**return 0;**

**}**

