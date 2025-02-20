#include<stdio.h>
#include<math.h>
int main(){
	int a;
	unsigned long long factorial=1;
	printf("enter a number");
	scanf("%d",&a);
	if(a<0){
		printf("factorial of a negative number does not exist");
	} else{
		for(int i=1; i<a; i++){
			factorial*=i;
		}
		printf("factorial of %d = %llu\n",a,factorial);
	}
	return 0;
}
