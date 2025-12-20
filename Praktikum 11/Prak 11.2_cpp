#include <iostream>
#include <fstream>

using namespace std;

int main() {
	ifstream myFile;
	string teks;
	
	myFile.open("data.txt");
	getline(myFile, teks);
	
	cout << "=== Isi File 'data.txt' ===" << endl;
	cout << teks << endl;
	
	myFile.close();
	
	string semuaBaris;
	string satuBaris;
	
	myFile.open("data.txt");
	
	while (!myFile.eof()) {
		getline(myFile, satuBaris);
		semuaBaris += satuBaris + "\n";
	}
	
	cout << "\n=== Isi File 'data.txt' lebih dari satu baris ===" << endl;
	cout << semuaBaris << endl;
	
	myFile.close();
}
