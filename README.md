#include <iostream>
#include <string>
using namespace std;

int main() {
    string nama;

    cout << "Silahkan inputkan nama Anda: ";
    getline(cin, nama);  // agar bisa membaca nama dengan spasi

    cout << "Hello " << nama << endl;

    return 0;
}
