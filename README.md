# Lecture-11
rising stars while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int i = 1, j = 1;
        while (i <= 5)
        {
            j = 1;
            while (j <= i)
            {
                cout << "*"; //print 5 stars
                j++;
            }
            cout << endl;
            i++;
        }

    }
falling stars while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int i = 1, j = 1;
        while (i <= 5)
        {
            j = i;
            while (j <= 5)
            {
                cout << "*"; //print 5 stars
                j++;
            }
            cout << endl;
            i++;
        }

    }
rising and fall stars while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int i = 1, j = 1;
        while (i <= 5)
        {
            j = 1;
            while (j <= i)
            {
                cout << "*"; //print 5 stars
                j++;
            }
            cout << endl;
            i++;
        }


        int x = 1, y = 1;
        while (x <= 5)
        {
            y = x;
            while (y <= 5)
            {
                cout << "*"; //print 5 stars
                y++;
            }
            cout << endl;
            x++;
        }
    }
table for loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int y;
        cout << "Enter a number you want the table of: " << endl;
        cin >> y;
        while (cin.fail())
        {
            cout << "Invalid command enter the numbers again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> y;
        }
        for (int x = 0; x <= 10; x++)
        {
            cout << y << " x " << x << " = " << y * x << endl;

        }

    }
table while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int y, x = 0;
        cout << "Enter a number you want the table of: " << endl;
        cin >> y;
        while (cin.fail())
        {
            cout << "Invalid command enter the number again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> y;
        }
        while (x <= 10)
        {
            cout << y << " x " << x << " = " << y * x << endl;
            x++;
        }

    }
table limit while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int y, x, z = 0;
        cout << "Enter a number you want the table of as well as till which number you want it to be printed example 10 etc.: " << endl;
        cin >> y >> x;
        while (cin.fail())
        {
            cout << "Invalid command enter the numbers again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> y >> x;
        }
        while (y <= 10)
        {
            cout << y << " x " << z << " = " << y * z << endl;
            z++;
        }

    }
table limit for loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int x;
        cout << "Enter a number you want the table of:" << endl;
        cin >> x;
        while (cin.fail())
        {
            cout << "Invalid command enter the numbers again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> x;
        }
        int y;
        cout << "Enter a number till which number you want it to be printed example 10 etc.: " << endl;
        cin >> y;
        while (cin.fail())
        {
            cout << "Invalid command enter the numbers again: " << endl;
            cin.clear();
            cin.ignore(1000, '\n');
            cin >> y;
        }
        for (int z = 0; z <= y; z++)
        {
            cout << x << " x " << z << " = " << x * z << endl;

        }

    }
9s do while loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int x = 100, sum = 0;
        do
        {

            if (x % 9 == 0)
            {
                cout << "\nNumber is " << x << endl;

                sum = sum + x;

            }
            x++;

        } while (x <= 200);

        cout << "The sum is " << sum << endl;
    }
factorial for loop

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        cout << "Enter the number for factorial\n";
        int x, fact=1;
        cin >> x;
        for (int y = x; y > 0; y--)
        {
           fact = y*fact;
        }
        cout << "The factorial is: " << fact;
    }
