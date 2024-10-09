# array-in-c
#include<stdio.h>


int main(){


int marks[10] = {56, 70,67,39,43,98,78,87,58,27};
int i, sum = 0;
float avrg;


for(i = 0; i<=9; i++){
	sum += marks[i];
}

 avrg = (float) sum/10;
   
   printf("The avareg number:%f\n", avrg );
   return 0;

}
