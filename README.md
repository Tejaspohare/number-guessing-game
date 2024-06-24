# number-guessing-game
#include<iostream>
using namespace std;
int main()
{
int number = 45;
int GuessedNumber;
bool isGuessed = true;
do{
cout<<"Guess the number";
cin>>GuessedNumber;
if(number > GuessedNumber)
{
cout<<"actual number is greater than"<<GuessedNumber<<endl;
GuessedNumber = false'
}
else if (number < GuessedNumber)
{
cout<<"actual number is less than"<<GuessedNumber<<endl;
isGuessed = false;
}
else if (number == GuessedNumber)
{
cout<<"you won!"<<endl;
isGuessed = false;
}
}
while(isGuessed == false);
}
