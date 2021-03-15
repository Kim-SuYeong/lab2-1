# lab2-1
lab2-1
#include <stdio.h>
int main()
{
    printf("[----- [김수영]  [2020039042] -----]\n");
    char charType;              //문자형 변수 charType
    int integerType;            //정수형 변수 integerType
    float floatType;            //부동 소수점형(float) 변수 floatType
    double doubleType;          //부동 소수점형(double) 변수 doubleType

    printf("Size of char: %ld byte\n",sizeof(charType));      
//변수 charType 크기를 구하며, charType은 char형으로 선언했으므로 크기는 1 byte
    printf("Size of int: %ld bytes\n",sizeof(integerType));  
//변수 integerType 크기를 구하며, integerType은 int형으로 선언했으므로 크기는 4 byte
    printf("Size of float: %ld bytes\n",sizeof(floatType)); 
//변수 floatType 크기를 구하며, floatType은 float형으로 선언했으므로 크기는 4 byte
    printf("Size of double: %ld bytes\n",sizeof(doubleType)); 
//변수 doubleType 크기를 구하며, doubleType은 double형으로 선언했으므로 크기는 8 byte

    printf("-----------------------------------------\n");

    printf("Size of char: %ld byte\n",sizeof(char));   
//문자형 자료형 char의 크기를 구하며, 크기는 1 byte
    printf("Size of int: %ld bytes\n",sizeof(int));   
//정수형 자료형 int의 크기를 구하며, 크기는 4 byte
    printf("Size of float: %ld bytes\n",sizeof(float));  
//부동 소수점형 자료형 float의 크기를 구하며, 크기는 4 byte
    printf("Size of double: %ld bytes\n",sizeof(double));  
//부동 소수점형 자료형 double의 크기를 구하며, 크기는 8 byte

    printf("-----------------------------------------\n");

    printf("Size of char*: %ld byte\n",sizeof(char*)); 
    printf("Size of int*: %ld bytes\n",sizeof(int*));
    printf("Size of float*: %ld bytes\n",sizeof(float*));
    printf("Size of double*: %ld bytes\n",sizeof(double*));
//char*, int*, float*, double* 모두 포인터 변수이므로 크기는 4 byte
    return 0;
}
