#include <iostream>
#include <Windows.h>
using namespace std;

int main() {
    setlocale(LC_ALL, "ru");
    int num;

    cout << "Введите число: ";
    cin >> num;

    if (num % 2 == 0)
        cout << "Число чётное\n";
    else
        cout << "Число нечётное\n";

    return 0;
}
