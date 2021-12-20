# Lecture-Math

//EXERCISE

Write a program that asks the user to enter a number and print the square and cube root

    #include <iostream>
    using namespace std;
    int main()
    {
        cout << "The cube of 8 is " << pow(8, 3) << endl;

        cout << "The square-root of 8 is " << sqrt(8) << endl;
        cout << "The square-root of 8 is " << sqrt(8) << pow(8, 1 / 2) << endl;

        cout << "The cube-root of 8 is " << cbrt(8) << endl;
        cout << "The cube-root of 8 is " << pow(8,1/3) << endl;
    }

---

    #include <iostream>
    #include <string>
    #include <array>
    #include <math.h>
    using namespace std;
    int main()
    {
        double n;
        cout << "Enter a number: " << endl;
        cin >> n;

        cout << "The cube of " << n <<" is " << pow(n, 3) << endl;

        cout << "The square-root of " << n << " is " << sqrt(n) << endl;
        cout << "The square-root of " << n << " is " << sqrt(n) << pow(n, 1 / 2) << endl;

        cout << "The cube-root of " << n << " is " << cbrt(n) << endl;
        cout << "The cube-root of " << n << " is " << pow(n,1/3) << endl;
    }

---

    #include <iostream>
    #include <string>
    #include <array>
    #include <math.h>
    using namespace std;
    int main()
    {
        double n;
        cout << "Enter a number: " << endl;
        cin >> n;

        while (cin.fail())
        {
            cout << "\nInvalid command enter the number again: \n" ;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> n;
        }

        cout << "The square-root of " << n << " is " << sqrt(n) << endl;
        cout << "The cube-root of " << n << " is " << cbrt(n) << endl;

    }








