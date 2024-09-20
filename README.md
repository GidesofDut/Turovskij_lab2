https://drive.google.com/file/d/1da89mrMPJ_t-t7zLMoV1nj9d5wItBP5H/view?usp=drivesdk

#include <iostream>

using namespace std;

int main(){

 int number = 20;

 cout<< «Дільник числа « << number << « - «;

 for (int i = 1 ; i <= number; ++i){

 if (number % i == 0){

 cout<< i << «;»;

 }

 }

 return 0;

}
