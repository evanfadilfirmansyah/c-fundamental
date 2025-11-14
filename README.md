#include <iostream>
using namespace std;

class Mobil {
public:
    string merk;
    int tahun;

    void info() {
        cout << "Merk: " << merk << ", Tahun: " << tahun << endl;
    }
};

int main() {
    Mobil m;
    m.merk = "Toyota";
    m.tahun = 2020;

    m.info();
    return 0;
}
