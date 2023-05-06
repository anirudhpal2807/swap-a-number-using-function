# swap-a-number-using-function
#include <iostream>
using namespace std;
 void swap(int *x,int *y){
 int temp;
 temp=*x;
 *x=*y;
 *y=temp;}
int main(){
   {int num1,num2;
   cin>>num1>>num2;
    swap(&num1,&num2);
    cout<<"first number is"<<num1<<endl;
      cout<<"second n  "<<num2<<endl;}

    return 0;
}
