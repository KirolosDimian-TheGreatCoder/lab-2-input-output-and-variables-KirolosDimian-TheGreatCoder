// Kirolos Dimian
// Lab 2
// 9/17/24

#include <iostream>
#include <string>
using namespace std;
int main ()
{
    // Part 1
    // Declaring variables
    string CerealName; // Declaring the variable name of string
    double calPerServing; // Declaring the variable name of double
    double ozPerServing; // Declaring the variable name of double
    double calPerOz; // Declaring the variable name of double
    

    // Asking for user's input
    cout << endl; // Empty line
    cout << "Write a name of a cereal (If it is more than one word, please combine to make it one word): " << endl; // Words to display
    cin >> CerealName; // The code that allows or user input
    cout << "Write the amount of calories per serving: " << endl; // Words to display
    cin >> calPerServing; // The code that allows or user input
    cout << "Write the amout of ounces per serving: " << endl; // Words to display
    cin >> ozPerServing; // The code that allows or user input

    // To find calories per ounce
    calPerOz = calPerServing / ozPerServing;

    // Final statement
    cout << "One serving of " << CerealName << " is " << ozPerServing <<  " ounces and has " <<calPerOz << " calories per ounce." << endl;
    
    // Part 2
    
    // Declaring New Variables
    double CalYouWantToEat; // Declaring the variable name of double
    double OzYouWantToEat; // Declaring the variable name of double
    

    //User input
    cout << endl; // Empty line
    cout << "How many calories do you want to eat today: " << endl; // Words to display
    cin >> CalYouWantToEat; // The code that allows or user input

    // Equation
    OzYouWantToEat = CalYouWantToEat / calPerOz;


    // Statement
    cout << "You can eat " << OzYouWantToEat << " ounces" << endl;

    return 0;
}

// My output
/*
Write a name of a cereal (If it is more than one word, please combine to make it one word): 
Habibi
Write the amount of calories per serving: 
100
Write the amout of ounces per serving: 
10
One serving of Habibi is 10 ounces and has 10 calories per ounce.

How many calories do you want to eat today:
1000
You can eat 100 ounces
*/