# pointers
pointer applications

#include <stdio.h>
#include <stdlib.h>


int main(int argc, char *argv[]) {
	
	int *ptr1,*ptr2,*ptr3,a;
	
	ptr1=a=3;
	ptr2=&ptr1;
	ptr3=&ptr2;
	
	printf("a'nin degeri=%d\n",a);
	printf("a'nin adresi=%d\n",&a);
	printf("a'nin adresinin adresi=%d\n",ptr2);
	printf("a'nin adresinin adresinin adresi=%d\n",ptr3);
	
	return 0;
}
