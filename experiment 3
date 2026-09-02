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




Sort code in array 



#include <iostream>
using namespace std;

void readArray(int arr[], int n)
{
    cout << "Enter " << n << " elements: ";
    for (int i = 0; i < n; i++)
    {
        cin >> arr[i];
    }
}

void displayArray(int arr[], int n)
{
    for (int i = 0; i < n; i++)
    {
        cout << arr[i] << " ";
    }
    cout << endl;
}

void swapNumbers(int &a, int &b)
{
    int temp = a;
    a = b;
    b = temp;
}

void sortArray(int arr[], int n)
{
    for (int i = 0; i < n - 1; i++)
    {
        for (int j = 0; j < n - i - 1; j++)
        {
            if (arr[j] > arr[j + 1])
            {
                swapNumbers(arr[j], arr[j + 1]);
            }
        }
    }
}

int main()
{
    int n;

    cout << "Enter the size of the array: ";
    cin >> n;

    int arr[n];

    readArray(arr, n);

    cout << "\nOriginal Array: ";
    displayArray(arr, n);

    sortArray(arr, n);

    cout << "Sorted Array: ";
    displayArray(arr, n);

    return 0;
}



