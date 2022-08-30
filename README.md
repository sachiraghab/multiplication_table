# multiplication_table
#include <iostream>
using namespace std;
int main() {
    int n;
    cout << "Enter a number: ";
    cin>>n;
    cout<<"Multiplication table of "<<n;
    cout<<"\n";
    //Multiplication table for a given number n
    for(int i=1; i<=10; i++){
    cout<<"\n"<<n<<" X "<<i<<" = "<<n*i;
cout<<"\nThank you";
    }
    return 0;
}
