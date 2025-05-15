// Online C++ compiler to run C++ program online

//Topics covered: Strlen,strcat,strncat,strcpy
#include <iostream>
#include <string.h>
using namespace std;


int main() {
    
  /*  char c[20];
    char s[20];
    
    cout<<"Enter first string"<<endl;
     cin.getline(c,20);
    cout<<"Enter second string"<<endl;
   
    cin.getline(s,20);
    char p[20];
    char k[20];
    cout<<"Enter third string"<<endl;
    cin.getline(p,20);
    cout<<"Enter fourth string"<<endl;
    cin.getline(k,20);
    
    char m[20];
    char n[20];
     cout<<"Enter fifth string"<<endl;
    cin.getline(m,20);
    cout<<"Enter sixth string"<<endl;
    cin.getline(n,20);
    
    cout<<"The string length is "<<strlen(s)<<endl; //String length function
    cout<<"The copied string is : "<<strcpy(k,p)<<endl; //String copy function, second string is copied to first function
    
    
     cout<<"The concatinated string is "<<strcat(c,s)<<endl;
     //String function to concatinate two strings
    
    cout<<"Three letters will be copied from n to m :" <<strncat(m,n,3)<<endl; //string function to copy desired number of letters from second string to first string 
    */
     
     char a[20]= "Programming";
     char b[20]= "psgfs";
    // cout<<"Occurence of string b in a " <<strstr(a,b); //to check for a string
   //  cout<<"Occurence of the character in the string is " <<strchr(a,'r')<<endl;
  // cout<<"Occurence of the character in the string is " <<strrchr(a,'i')<<endl;
  
  cout<<"Comparing two strings " <<strcmp(a,b)<<endl;
     
    
    
    
    
    
    return 0;
    
}
    
    
