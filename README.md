#include<iostream>
using namespace std;
int main()
{
 double num1,num2;
 char operation;
 cout<<"simple calculator"<<endl;
 cout<<"-----------------"<<endl;
 cout<<"enetr the first number:";
 cin>>num1;
 cout<<"enter an operator (+,-,*,/):";
 cin>>operation;
 cout<<"enter the second number:";
 cin>>num2;
 switch (operation)
 {
 	case '+':
 		cout<<"result:"<<num1+num2<<endl;
 		break;
 		case '-':
 			cout<<"result:"<<num1-num2<<endl;
 			break;
 			case '*':
 				cout<<"result:"<<num1*num2<<endl;
 				break;
 				case '/':
 				if(num2 !=0)
 				{
 					cout<<"result:"<<num1/num2<<endl;
				 }
				 else
				 {
				 	cout<<"error: divison by zero is not allowed!"<<endl;
				 }
				 break;
				 default:
				 	cout<<"error: invaild operator!"<<endl;
	 }	
	 return 0;
}
