# CURRENCY-CONVERTER-IN-CPP


#include<iostream>
using namespace std;
int main(){
    float dollar;
    cout<<"Enter the currency in dollar : ";
    cin>>dollar;

    float bp=dollar*0.81;
    cout<<"The amount in british pound is : "<<bp<<endl;

    float ir=dollar*82.56;
    cout<<"The amount in indian rupees is : "<<ir<<endl;

    float ff=dollar*0.93;
    cout<<"The amount in french franc is : "<<ff<<endl;

    float gd=dollar*1.82;
    cout<<"The amount in german deutschmark is : "<<gd<<endl;

    float jy=dollar*140.66;
    cout<<"The amount in japanese yen is : "<<jy<<endl;

    float kw=dollar*1323.43;
    cout<<"The amount in korean won is : "<<kw<<endl;

return 0;
}
