# Sum-of-natural-numbers-using-GOTO-
Method 02


#include<iostream>
using namespace std;
int main(){
int a,c=0;
cout<<"Enter a number: ";
cin>>a;//3
sum:

c=c+a;//3//5//6
a--;//2//1//0
if(a!=0){
goto sum;
}
cout<<"sum ="<<c;//6
}
