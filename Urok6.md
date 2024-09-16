#include <iostream>
#include <string>
using namespace std; 
int main() 
{ 
    //Задание1 
    int k=3, j=4, l=1, m=2; 
    int a = k+j; 
    int b = j-l; 
    int c = j*m; 
    int d = j/m; 
    int h = j%k; 
    cout << "k + j = " << a << endl; 
    cout << "j - l = " << b << endl; 
    cout << "m * j = " << c << endl; 
    cout << "j / m = " << d << endl; 
    cout << "j % k = " << h << endl; 
    //Задание2 
    cout << boolalpha; 
    int k1=6, j1=3, l1=6, m1=2; 
    cout << (k1==l1) << endl; 
    cout << (j1==m1) << endl; 
    cout << (k1!=j1) << endl; 
    cout << (l1!=k1) << endl; 
    cout << (k1>j1) << endl; 
    cout << (j1>k1) << endl; 
    cout << (j1<l1) << endl; 
    cout << (k1<m1) << endl; 
    cout << (k1>=l1) << endl; 
    cout << (m1>=l1) << endl; 
    cout << (m1<=l1) << endl; 
    cout << (k1<=j1) << endl; 
    //Задание3 
    int k2=4, j2=10, l2=4, m2=10; 
    cout << "true = " << (k2 == l2 && j2 == m2) << endl; 
    cout << "true = " << (k2 != m2 && j2 != l2) << endl; 
    cout << "true = " << (k2 == l2 || l2 == m2) << endl;
    cout << "true = " << (k2 != m2 || j2 == m2) << endl;
    cout << "true = " << !(k2 == m2 && j2 == l2) << endl;
    cout << "true = " << !(k2 != l2 || j2 != m2) << endl;
} 
