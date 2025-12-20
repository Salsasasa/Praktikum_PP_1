#include <iostream>
using namespace std;

int main() {
    string arr[] = {"Ahyeon","Chiquita","Pharita","Naila","Asa","Rora"};
    int size = sizeof(arr) / sizeof(arr[0]);
    bool find = false;

    string target = "Naila";

    for (int i = 0; i < size; i++) {
        if (arr[i] == target) {
            cout << "Nama " << arr[i] << " ditemukan pada index ke-" << i;
            find = true;
            break;
        }
    }

    if (!find) {
        cout << "Data tidak ditemukan";
    }

    return 0;
}
