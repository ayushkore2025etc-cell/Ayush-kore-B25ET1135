#include <iostream>
using namespace std;

int main() {
    int num;

    cout << "enter the number :";
    cin >> num;

    int sum = 0;

    for (int i = 0; i <= num; i++) {
        if (i % 2 == 0) {
            sum += i;
        }
    }

    cout << "the sum is " << sum << endl;

    for (int i = 0; i <= num; i++) {
        if (i % 2 == 0) {
            sum += i;
            cout << i << " ";
        }
    }

    return 0;
}



