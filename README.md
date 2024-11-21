include <iostream>
using namespace std;
int main() 
  {

    int n,num,digit,rev= 0;

     cout<<"Enter the Positive number:";
     cin>>num;
     n= num;

     while  (num)
{
      digit= num%10;
      rev= (rev*10) + digit;
      num= num/10;
}
      cout<<"The Reversed number is:"<<rev<<endl;
      if (n== rev)
      
      cout<<"It is a Palindrome";

       else

       cout<<"It is not a Palindrome";

  return 0;
}
