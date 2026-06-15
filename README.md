# cpp-calculator-learning-project-
Simple calculator built using C++ Concepts used: - switch statement - arithmetic operators - user input/output
{ content :}
#include <iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter a value a"<<endl;
    cin>>a;
    cout<<"Enter a value of b"<<endl;
	cin>>b;
    char op;
    cout<<"Enter the operations you want to perform "<<endl;
    cin>>op;
    switch(op){
        case '+': cout<< (a+b) <<endl;
                  break;
        case '-': cout<< (a-b) <<endl;
                  break;
        case '*': cout<< (a*b) <<endl;
                  break;
        case '/': cout<< (a/b) <<endl;
                  break;
        case '%': cout<< (a%b) <<endl;
                  break;
        default : cout<<"please enter a valid operations" ;      
    }
        return 0;
        
} 
{content:}

