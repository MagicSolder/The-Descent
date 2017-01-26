#include <iostream>
#include <string>
#include <vector>
#include <algorithm>

using namespace std;


int main()
{
  while (1) {
      
    int hg = 0 ; //Высота
    int shoot = 0; 
    
    
        for (int i = 0; i < 8; i++) {
            int mountain_h; // represents the height of one mountain.
            cin >> mountain_h; cin.ignore();  
             if (hg < mountain_h) {
              hg = mountain_h;
              shoot = i;
                }
            } 
           cout << shoot << endl; // Cбивание башен
       }
}
