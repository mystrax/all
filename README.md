# all
// IntroTo Programming.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

//#include <iostream>
//using namespace std;
//int main()

    /*Mark my words*/
    /*cout << "Enter the marks from 1-100 to see the grade, 0 input is not accepted\n";
    double m;
    cin >> m;
    if (m > 70)
    {
        cout << "You have a A Grade";
    }
    else if (m >= 60 && m < 70)
    {
        cout << "You have a B Grade";
    }
    else if (m >= 50 && m < 60)
    {
        cout << "You have a C Grade";
    }
    else if (m > 40 && m < 50)
    {
        cout << "You have a D Grade";
    }
    else if (m == 40)
    {
        cout << "You have a JUST PASSED Grade";
    }
    else if (m < 40 && m != 0)
    {
        cout << "You have a Fail Grade";
    }
    else
    {
        cout << "Wrong input";
    }*/
	
	/*double mag;
	cout << "please enter the mangitude of the earthquake in numbers 0 input is not accepted : ";
	cin >> mag;



	if (mag < 2.0 && mag >0) {
		cout << " earthquake is considered to be a micro earthquake.";
	}
	else if (mag >= 2.0 && mag < 3)
	{
		cout << mag << " earthquake is considered to be a very minor earthquake.";
	}
	else if (mag >= 3.0 && mag < 4)
	{
		cout << mag << " earthquake is considered to be a minor earthquake.";
	}
	else if (mag >= 4.0 && mag < 5.0)
	{
		cout << mag << " earthquake is considered to be a light earthquake.";
	}
	else if (mag >= 5.0 && mag < 6.0)
	{
		cout << mag << " earthquake is considered to be a moderate earthquake." << endl;
	}
	else if (mag >= 6.0 && mag < 7)
	{
		cout << mag << " earthquake is considered to be a strong earthquake." << endl;
	}
	else if (mag >= 7.0 && mag < 8)
	{
		cout << mag << " earthquake is considered to be a major earthquake." << endl;
	}
	else if (mag >= 8.0 && mag <= 10)
	{
		cout << mag << " earthquake is considered to be a great earthquake." << endl;
	}
	else if (mag > 10.0)
	{
		cout << mag << " earthquake is considered to be a meteoric earthquake." << endl;
	}

	else {
		cout << "You entered an invalid value" << endl;
	}
	return 0;*/

//}cout << "Enter a letter to see whether its a vowel or consonant\n";
//char c;
//cin >> c;
////isalpha is a built in function to check for alphabet values in c++
//if (!isalpha(c))
//{
//	cout << "you entered an incorrect value";
//}
//else if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' || c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U')
//{
//	cout << "you entered a vowel";
//
//}
//
//
//else
//{
//	cout << "you entered a consonant";
// 
//
//char l;
//int count1, count2; // variable for isalpha
//
//cout << "Enter a letter to check whether its a vowel or a consonant: ";
//cin >> l;
//if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u' || l == 'A' || l == 'E' || l == 'I' || l == 'O' || l == 'U') // Checking if the entered character is a vowel
//{
//	cout << "The input is a vowel." << endl;
//}
//count1 = isalpha(char(l)); // Using isalpha built-in function for alphabets
//count2 = isdigit(char(l)); // Using isdigit built-in function for digits
//if (count1 == 0 && count2 != 4) // Checking if the entered character is a special character, converting the special character into their ASCII code
//{
//	cout << "The input is a special character." << endl;
//}
//else if (count1 != 2 && count2 == 4) // Checking if the entered character is a digit
//{
//	cout << "The input is a digit." << endl;
//}
//else if (count1 != 0 && count2 != 4 && l != 'a' && l != 'e' && l != 'i' && l != 'o' && l != 'u' && l != 'A' && l != 'E' && l != 'I' && l != 'O' && l != 'U') // Checking if the entered character is a consonant
//{
//	cout << "The input is a consonant." << endl;
//}
//else
//{
//	cout << "The input is incorrect.";
//}
//return 0;
//}

//bool musician;
//string reply;
//string instrument;
//cout << "Do you play any musical instrument? \n type 'y' for yes \n and 'n' for no \n ";
//cin >> reply;
//if (reply == "y" || reply == "Y")
//{
//	musician = true;
//	if (musician == true)
//	{
//		cout << "What kind of insturment you can play \n type d if you're a drummer \n type g if you're a guitarist\n type o for other\n" << endl;
//		cin >> instrument;
//		if (instrument == "g" || instrument == "G")
//		{
//			cout << "That's great! I really needed a guitarist." << endl;
//		}
//		else if (instrument == "d" || instrument == "D")
//		{
//			cout << "That's great! I really needed a drummer." << endl;
//		}
//		else if (instrument == "o" || instrument == "O")
//		{
//			cout << "Ah I see, actually I'm looking for guitarist or a drummer.\n Let me know if you someone who plays them\n Thank you :)" << endl;
//		}
//		else
//		{
//			cout << "Incorrect input" << endl;
//		}
//
//	}
//}
//else if (reply == "N" || reply == "n")
//{
//	musician = false;
//	cout << "Oh! so you don't know how to play any instrument\n it's alright, let me know if you know someone who does \n Thanks" << endl;
//}
//else
//{
//
//	cout << "Incorrect input" << endl;
//}return 0;

//bool musician;
//string reply;
//string instrument;
//cout << "Do you play any musical instrument? \n type 'y' for yes \n and 'n' for no \n ";
//cin >> reply;
//if (reply == "y" || reply == "Y")
//{
//	musician = true;
//	if (musician == true)
//	{
//		cout << "What kind of insturment you can play \n type d if you're a drummer \n type g if you're a guitarist\n type o for other\n" << endl;
//		cin >> instrument;
//		if (instrument == "g" || instrument == "G")
//		{
//			cout << "That's great! I really needed a guitarist." << endl;
//		}
//		else if (instrument == "d" || instrument == "D")
//		{
//			cout << "That's great! I really needed a drummer." << endl;
//		}
//		else if (instrument == "o" || instrument == "O")
//		{
//			cout << "Ah I see, actually I'm looking for guitarist or a drummer.\n Let me know if you someone who plays them\n Thank you :)" << endl;
//		}
//		else
//		{
//			cout << "Incorrect input" << endl;
//		}
//
//	}
//}
//else if (reply == "N" || reply == "n")
//{
//	musician = false;
//	cout << "Oh! so you don't know how to play any instrument\n it's alright, let me know if you know someone who does \n Thanks" << endl;
//}
//else
//{
//
//	cout << "Incorrect input" << endl;
//}
//
//
//return 0;
//	}
// 
// Rides
//// cout << "Please enter your height in meters to check whether you can ride or not\n";
//double h, age;
//cin >> h;
//cout << "Please enter your age to check whether you can ride or not\n";
//cin >> age;
//if (age >= 5 && h >= 0.6)
//{
//    cout << "You can ride";
//}
//else if (age < 5 && h < 0.5)
//{
//    cout << "Sorry you cannot ride";
//}
//else
//{
//    cout << "Incorrect input";
//}
//return 0;
//
// What is the capital of france
// 
// cout << "What is the capital of France?\n";
//string capital;
//cin >> capital;
//
//if (capital == "Paris" || capital == "paris" || capital == "PARIS")
//{
//    cout << "You enter the correct answer";
//}
//else
//{
//    cout << "Sorry wrong answer";
//}
//
//return 0;

//Write a program that works out if a number is odd or even

//int main() {
//    int n;
//
//    cout << "Enter a number:\n";
//    cin >> n;
//
//    if (n % 2 == 0)
//        cout << n << " is even.";
//    else
//        cout << n << " is odd.";
//
//    return 0;
//Write a program to check whether a number is positive, negative or zero.
//
//
//#include <iostream>
//
//using namespace std;
//int main()
//{
//	int num;
//	cout << "Enter the number" << endl;
//	cin >> num;
//	if (num > 0) {
//		cout << num << " is a positive number";
//	}
//	else if (num < 0) {
//		cout << num << " is a negative number";
//	}
//	else {
//		cout << "You entered Zero";
//	}
//	return 0;
//}
//Write a program to calculate profit or loss.The program should ask the user  for the purchase priceand sale price then calculate whether profit or loss was  made on the sale.
//
//
//# include <iostream>
//using namespace std;
//int main()
//{
//	int pp, sp, profit, loss;
//	cout << "Enter Purchase Price:" << endl;
//	cin >> pp;
//	cout << "Enter Sale price:" << endl;
//	cin >> sp;
//	if (sp > pp)
//	{
//		profit = sp - pp;
//		cout << "profit" << profit << endl;
//	}
//	else if (pp > sp)
//	{
//		loss = pp - sp;
//		cout << "Loss of " << loss << endl;
//	}
//	else
//	{
//		cout << "No Profit no Loss.";
//	}
//}
//Name a shape
//
//#include <iostream>
//using namespace std;
//int main()
//{
//	int shapeSides;
//	cout << "How many sides does the shape have?\n" << endl;
//	cin >> shapeSides;
//
//	if (shapeSides == 3)
//	{
//		cout << "The shape is a triangle\n" << endl;
//	}
//	else if (shapeSides == 4)
//	{
//		cout << "The shape is a square\n" << endl;
//	}
//	else if (shapeSides == 5)
//	{
//		cout << "The shape is a pentagon\n" << endl;
//	}
//	else if (shapeSides == 6)
//	{
//		cout << "The shape is a hectagon\n" << endl;
//	}
//	else if (shapeSides == 7)
//	{
//		cout << "The shape is a heptagon\n" << endl;
//	}
//	else if (shapeSides == 8)
//	{
//		cout << "The shape is a octagon\n" << endl;
//	}
//	else if (shapeSides == 9)
//	{
//		cout << "The shape is a nonagon\n" << endl;
//	}
//	else if (shapeSides == 10)
//	{
//		cout << "The shape is a decagon\n" << endl;
//	}
//	else
//	{
//		cout << "The shape is not identified\n" << endl;
//	}
//}
//int myGrade;
//cout << "Type the percentage of your grade?\n";
//cin >> myGrade;
//
//if (myGrade >= 70)
//{
//    cout << "Your grade is A.\n";
//}
//else if ((myGrade > 59) && (myGrade < 69))
//{
//    cout << "Your grade is B.\n";
//}
//else if ((myGrade > 49) && (myGrade < 59))
//{
//    cout << "Your grade is C.\n";
//}
//else if ((myGrade > 39) && (myGrade < 49))
//{
//    cout << "Your grade is D.\n";
//}
//else
//{
//    cout << "Your grade is F.\n";
//}
//    }
//Killing time
//
//include <iostream>
//using namespace std;
//int main()
//{
//    int time;
//    int money;
//    cout << "State if your friend is going to be late or early than 15 minutes\n";
//    cin >> time;
//    if (time >= 15)
//    {
//        cout << "If you have more than 5 AED you can buy a coffee.\n";
//        cin >> money;
//        if (money > 5)
//        {
//            cout << "Nice! I can get a coffee." << endl;
//        }
//        else
//        {
//            cout << "Go around the town for a walk.\n";
//        }
//    }
//    else
//    {
//        cout << " I'll wait for him in the meeting up place.\n";
//    }
//    return 0;
//
//cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
//double time;
//cin >> time;
//if (time < 12)
//{
//	cout << "Good Morning";
//}
//else if (time >= 12 && time < 18)
//{
//	cout << "Good Afternoon";
//}
//else if (time >= 18 && time < 21)
//{
//	cout << "Good Evening";
//}
//else if (time >= 21 && time < 24)
//{
//	cout << "Good Night";
//}
//else
//{
//	cout << "Incorrect input";
//}
//vote
//cout << "Kindly enter your age to see whether you can vote or not!\n";
//int age;
//cin >> age;
//if (age >= 18)
//{
//	cout << "You can vote";
//
//}
//else
//{
//	cout << "Sorry not today";
//}
//ODD EVEN
//cout << "Enter the number to see whether its even or odd\n";
//int number;
//cin >> number;
//if (number % 2 == 0)
//{
//    cout << "\nThe entered number is Even\n";
//}
//else if (number % 2 != 0)
//{
//    cout << "The number entered is odd";
//}
//else
//{
//    cout << "Incorrect";
//}
//positive negative
//cout << "Enter the number to see whether its positive, negative or zero\n";
//double number;
//cin >> number;
//if (number == 0)
//{
//    cout << "The number you entered is zero";
//}
//
//else  if (number > 0)
//{
//    cout << "The number you entered is positive";
//}
//else  if (number < 0)
//{
//    cout << "The number you entered is negative";
//}
//else
//{
//    cout << "Incorrect input";
//}
//
//Write a program to calculate profit or loss.The program should ask the user  for the purchase priceand sale price then calculate whether profit or loss was  made on the sale.
//
//
//# include <iostream>
//using namespace std;
//int main()
//{
//	int pp, sp, profit, loss;
//	cout << "Enter Purchase Price:" << endl;
//	cin >> pp;
//	cout << "Enter Sale price:" << endl;
//	cin >> sp;
//	if (sp > pp)
//	{
//		profit = sp - pp;
//		cout << "profit" << profit << endl;
//	}
//	else if (pp > sp)
//	{
//		loss = pp - sp;
//		cout << "Loss of " << loss << endl;
//	}
//	else
//	{
//		cout << "No Profit no Loss.";
//	}
//}
//Name a shape
//
//	int shapeSides;
//	cout << "How many sides does the shape have?\n" << endl;
//	cin >> shapeSides;
//
//	if (shapeSides == 3)
//	{
//		cout << "The shape is a triangle\n" << endl;
//	}
//	else if (shapeSides == 4)
//	{
//		cout << "The shape is a square\n" << endl;
//	}
//	else if (shapeSides == 5)
//	{
//		cout << "The shape is a pentagon\n" << endl;
//	}
//	else if (shapeSides == 6)
//	{
//		cout << "The shape is a hectagon\n" << endl;
//	}
//	else if (shapeSides == 7)
//	{
//		cout << "The shape is a heptagon\n" << endl;
//	}
//	else if (shapeSides == 8)
//	{
//		cout << "The shape is a octagon\n" << endl;
//	}
//	else if (shapeSides == 9)
//	{
//		cout << "The shape is a nonagon\n" << endl;
//	}
//	else if (shapeSides == 10)
//	{
//		cout << "The shape is a decagon\n" << endl;
//	}
//	else
//	{
//		cout << "The shape is not identified\n" << endl;
//	}
//}
//Switch 
//int a, b;
//cout << "Enter two numbers.\n";
//cin >> a >> b;
//cout << "Pick a calculation\n";
//cout << "1:Addition\n2: Subtraction\n3: Multiplication\n4: Division" << endl;
//int input;
//cin >> input;
//switch (input)
//{
//case 1:
//	cout << (a + b);
//	break;
//case 2:
//	cout << (a - b);
//	break;
//case 3:
//	cout << (a * b);
//	break;
//case 4:
//	cout << (a / b);
//	break;
//}
//{
//char input;
//cout << "Would you like to continue? type (Y or N):";
//cin >> input;
//switch (input)
//{
//case 'y':
//case 'Y':
//	cout << "Round 1! Fight\n";
//	break;
//case 'n':
//case 'N':
//	cout << "YOU LOSE!";
//	break;
//default:
//	cout << "Input is invalid\n";
//}
//}
//int input;
//cout << "What month is it?Type the month in a number way. Example if its January type 1\n";
//cin >> input;
//switch (input)
//{
//case 1:
//    cout << "January have 31 days.";
//    break;
//case 2:
//    cout << "February have 28/29 days.";
//    break;
//case 3:
//    cout << "March have 31 days.";
//    break;
//case 4:
//    cout << "April have 30 days.";
//    break;
//case 5:
//    cout << "May have 31 days.";
//    break;
//case 6:
//    cout << "June have 30 days.";
//    break;
//case 7:
//    cout << "July have 31 days.";
//    break;
//case 8:
//    cout << "August have 30 days.";
//    break;
//case 9:
//    cout << "September have 31 days.";
//    break;
//case 10:
//    cout << "October have 30 days.";
//    break;
//case 11:
//    cout << "November have 31 days.";
//    break;
//case 12:
//    cout << "December have 30 days.";
//    break;
// 
// 
// cout << "Kindly enter how many litres you want to fill up your car\n";
//int lit;
//cin >> lit;
//if (lit != 0)
//{
//    cout << "You have selected " << lit << " litres\n";
//    cout << "Kindly select the fuel type you want for your car\n";
//    cout << "Enter 'p' for Petrol\n 'd' for Diesel\n";
//    char fuel;
//    cin >> fuel;
//    switch (fuel)
//    {
//    case 'P':
//    case 'p':
//    {
//
//        cout << "You have selected Petrol for filling up your car\n ";
//        int c;
//        c = lit * 0.8;
//        cout << "\nThe price per litres is 0.8 now the total is " << c;
//        break;
//    }
//    case 'd':
//    case 'D':
//    {
//        cout << "You have selected Diesel for filling up your car ";
//        int c;
//        c = lit * 0.5;
//        cout << "\nThe price per litres is 0.5 now the total is " << c;
//        break;
//
//        break;
//    }
//
//    default:
//    {
//        cout << "Incorrect command"; break;
//    }
//    }
//}
//else
//{
//    cout << "Incorrect command\n ";
//}
// {
//char input;
//cout << "What is the capital of France?" << "Type R for Rome, Type P for Paris, type V for Venice" << endl;
//cin >> input;
//switch (input)
//{
//
//case 'P':
//case 'p':
//{
//    cout << "Correct! The Capital of France is Paris" << endl;
//    break;
//}
//
//
//case 'R':
//case 'r':
//case 'v':
//case 'V':
//{
//    cout << "Incorrect. The Capital of France is Paris" << endl;
//    break;
//}
//
//default:
//{
//    cout << "Invalid Input" << endl;
//}
// shape switch
//int main()
//{
//int input;
//cout << "To know what shape it is, Type how many sides it has. Example if 4 sides then type 4\n";
//cin >> input;
//switch (input)
//{
//case 1:
//	cout << "invalid" << endl;
//	break;
//case 2:
//	cout << "invalid" << endl;
//	break;
//case 3:
//	cout << "The shape is a triangle" << endl;
//	break;
//case 4:
//	cout << "The shape is a square." << endl;
//	break;
//case 5:
//	cout << "The shape is a pentagon" << endl;
//	break;
//case 6:
//	cout << "The shape is a hexagon" << endl;
//	break;
//case 7:
//	cout << "The shape is a heptagon" << endl;
//	break;
//case 8:
//	cout << "The shape is an octagon" << endl;
//	break;
//case 9:
//	cout << "The shape is a nonagon" << endl;
//	break;
//case 10:
//	cout << "The shape is a decagon" << endl;
//	break;
//case 11:
//	cout << "The shape is a hendecagon." << endl;
//	break;
//case 12:
//	cout << "The shape is a dodecagon." << endl;
//	break;
//
//default:
//{
//	cout << "Incorrect Input" << endl;
//	break;
//}
//switch temp
// #include<iostream>
//using namespace std;
//int main()
//{
//    int temp;
//    cout << "Temperature Converter, Please choose  1: Celcius to Fahrenheit 2: Fahrenheit to Celcius \n\n";
//    cin >> temp;
//    switch (temp)
//    {
//    case 1:
//        int temp = (temp * 9 / 5) + 32;
//        cout << "Temperature is F =" << temp;
//        break;
//    case 2:
//        int temp = (32 - 32) * 5 / 9;
//        cout << "Temperature is C =" << temp;
//        break;
//    default:
//        cout << "Invalid Input";
//        break;
//    }
//}
//}
//}
//}
//}
// Run program: Ctrl + F5 or Debug > Start Without Debugging menu
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file
