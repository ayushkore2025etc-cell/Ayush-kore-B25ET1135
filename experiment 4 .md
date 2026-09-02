#include <iostream>
using namespace std;

class Complex {
    float real, imag;

public:
    void input() {
        cout << "Enter real part: ";
        cin >> real;

        cout << "Enter imaginary part: ";
        cin >> imag;
    }

    void square() {
        float realPart = (real * real) - (imag * imag);
        float imagPart = 2 * real * imag;

        cout << "Square of the complex number is: "
             << realPart << " + " << imagPart << "i";
    }
};

int main() {
    Complex c;

    c.input();
    c.square();

    return 0;
}
