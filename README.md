# Lab-13.40-
#include <iostream>
using namespace std;

int main() {
  double numChoice;
  double person = 1;
  int coffee = 0;
  int tea = 0;
  int soda = 0;
  int oJ = 0;

   
    cout << "1. Coffee" << endl;
    cout << "2. Tea" << endl;
    cout << "3. Soda" << endl;
    cout << "4. Orange Juice" << endl;
    cout << "-1 QUIT" << endl;
   

  cout << "Please input the favorite beverage, Choose 1, 2, 3, or 4 from the above menu or -1 to exit the program." << endl;
  cin >> numChoice; 

 while ((numChoice >=1) && (numChoice <=4 ))  { 
    person++;
    if (numChoice == 1) 
        coffee++; 
    cout << "Please input the favorite beverage of person " << person << " Choose 1, 2, 3, or 4 from the above menu or -1 to exit the program." << endl;
    if (numChoice == 2)
        tea++;
    if (numChoice == 3)
        soda++;
    if (numChoice == 4)
     oJ++;
    cin >> numChoice;
    }
 
 

 
cout << "The total amount of people survyed is " << person << endl;
cout << "The resutls as follows:" << endl << endl;

cout << "Beverage and Number of votes" << endl; 
cout << "Coffee:" << coffee << endl;
cout << "Tea:" << tea << endl;
cout << "Soda:" << soda << endl;
cout << "Orange Juice:" << oJ << endl;




}
