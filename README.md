#include<stdio.h>

float add(
        float fno1,  //First input
        float fno2   //Second input
    )
{
    float fAns=0.0;  //variable to store result
    fAns= fno1+ fno2;
    return fAns;
    
}

int main()
{
    
   
    float fValue1=0.0,  //variable to sotre first input
    fValue2=0.0,        //varibale to store second input
    fResult=0.0;        //variable to store return value

    printf("enter 2 nos");
    scanf("%f%f",&fValue1, &fValue2);

   fResult= add(fValue1,fValue2);

    printf("addition is: %f\n",fResult);
     return 0;
}
