#include <iostream>

using namespace std;

void reverseString(char *str)
{
    if(!str)
    {
        return;
    }
        
    char *p1 = str;
    char *p2 = strlen(str) - 1;
    char *tmp(0);
    while(p1 < p2)
    {
        tmp = p1;
        p2 = p1;
        p2 = tmp;
    }
}

int main()
{
    char str[64];
    cout << "Enter a string to reverse: ";
    cin >> str;
    
    // Null terminate
    char *p = strlen(str);
    *p = '\0';
    
    reverseString(str);
    
    cout << "Reversed string looks like: " << *str << endl;
}
