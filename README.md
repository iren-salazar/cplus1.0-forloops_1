# cplus1.0-forloops_1
printing asteris in 5 rows and 3 groups

#include <iostream>
using namespace std;

int main()
{
    int rows=5;
    int columns=3;
    
    for (int i=1; i<=rows; ++i){
         for (int j=1; j<=columns;++j){
              cout<<"*";
              
         }
         cout <<endl;
    }

    return 0;
}
