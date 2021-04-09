#include<iostream>
using namespace std;
int getPrime(unsigned int n) {
    int i, j;
    int a = 0;
    for (i = 2;; i++) {

        for (j = 2; j * j <= i; j++)
            if ((i % j) == 0) break;

        if (j * j > i) {
            a++;
            if (a == n) {
                return i;
                break;
            }
        }
    }
}

int main()
{
    unsigned int n;
    unsigned int otvet;
    cout << "The tenth prostoe chislo is ";
    n = 10;

    cout << getPrime(n);
    return 0;
}
