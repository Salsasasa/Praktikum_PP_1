#include <iostream>
#include <fstream>
#include <string>

using namespace std;

void registration();
void login();

void registration() {
    ofstream myFile, accList;
    string userReg;

    system("cls");
    cout << "------------ REGISTER ------------" << endl;
    cout << "Enter Username : ";
    cin >> userReg;
    cout << endl;

    myFile.open(userReg + ".txt");
    myFile << 0; 
    myFile.close();

    accList.open("ListAccount.txt", ios::app);
    accList << userReg << endl;
    accList.close();

    system("cls");
    cout << "Registration Successful!" << endl;
}

void login() {
    ifstream myFile;
    string userLog, userData;
    bool exist = false;

    system("cls");
    cout << "------------- LOGIN -------------" << endl;
    cout << "Enter Username : ";
    cin >> userLog;
    cout << endl;

    myFile.open("ListAccount.txt");
    while (myFile >> userData) {
        if (userData == userLog) {
            exist = true;
        }
    }
    myFile.close();

    if (exist == true) {
        system("cls");
        cout << "Login Successful!" << endl;

        int topScore;
        cout << "Input Top Score : ";
        cin >> topScore;

        ofstream scoreFile;
        ifstream scoreCheck;
        int currentScore = 0;

        scoreCheck.open(userLog + ".txt");
        scoreCheck >> currentScore;
        scoreCheck.close();

        if (topScore > currentScore) {
            scoreFile.open(userLog + ".txt");
            scoreFile << topScore << endl;
            scoreFile.close();
        }

        cout << "\nYour Top Score Is : " << topScore << endl;
    } 
    else {
        system("cls");
        cout << "------------------------- -------------" << endl;
        cout << "				LOGIN ERROR				" << endl;
        cout << "Please check your username and password" << endl;
        cout << endl;
    }
}

int main() {
    int choice;

    cout << "1. Registration" << endl;
    cout << "2. Login" << endl;
    cout << "Input Your Choice : ";
    cin >> choice;

    switch (choice) {
        case 1:
            registration();
            break;
        case 2:
            login();
            break;
        default:
            cout << "Invalid choice!" << endl;
    }

    return 0;
}
