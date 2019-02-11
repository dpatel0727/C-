//
//  Program Name:             Project1.cpp
//  Course:                   CSE 1311/Section 01
//  Student Name:             Dhruv Patel
//  Assignment Number:        Project1
//  Due Date:                 01/31/19
//

/* Purpose:
 Create a progam that prompts the user to enter the Length and Width of Yard in Sq. Feet and Length and Width of House in Sq. Feet. This program calculates the time to mow the yard in minutes and can also determine how much area to be cut in square feet. The formulas that i used are (GrassRemain = AreaOfYard -  AreaOfHouse) , (second = GrassRemain / TWO) , (minute = second / 60). In this program we also learned how to use CONSTANT variable. CONSTANT variable is TWO also used in the calculations.
 
 */

#include <iostream>
#include <iomanip>
#include <cmath>

using namespace std;

int main() {
    
    // Declaring The Variables
    const float TWO = 2.0;
    int YardLenWid, HouseLenWid;
    int TimeCutSec , TimeCutMin;
    int AreaOfHouse, AreaOfYard;
    int AreaCut;
    
    // Prompting Input From User
    cout << "Inpute Length and Width of Yard in Sq. Feet " << endl;
    cin >> YardLenWid;
    
    cout << "" << endl;
    cout << "Inpute Length and Width of House in Sq. Feet " << endl;
    cin >> HouseLenWid;
    cout << "" << endl;
    
    // Calculation
    AreaOfHouse = HouseLenWid;
    AreaOfYard = YardLenWid;
    
    AreaCut = AreaOfYard -  AreaOfHouse;
    TimeCutSec = AreaCut / TWO ;
    TimeCutMin = TimeCutSec / 60 ;
    
    // Print Out The Outputs
    cout << "" << endl;
    cout << "Length and Widht of Yard is " << YardLenWid << endl << endl;
    cout << "Length and Widht of House is " << HouseLenWid << endl << endl;
    cout << fixed << setprecision(2) << "Area to be cut in Square Feet: " << AreaCut << endl << endl;
    cout << "Time to mow the yard in Minutes: " << TimeCutMin << endl << endl;
    
    // Closing Statement
    cout << "" << endl;
    cout << "This Code is created by Dhruv Patel" << endl;
    cout << "" << endl;
    
    return 0;
}
