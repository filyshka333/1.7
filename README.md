#include <iostream> 
#include <math.h> 
using namespace std; 
class Number{ 
public: 
 void numb() 
 { 
  double pi = 3.1415926; 
  cout << setprecision(4) << pi << endl; 
 } 
 
}; 
int main() 
{ 
 Number num; 
 num.numb(); 
}
