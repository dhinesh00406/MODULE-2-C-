# Ex.No:5
# Ex.Name:Write a CPP Program to overload the Operator (++) i.e. on invoking it the incrementation should happen by some random value.
## Date:
## Aim:
To write a CPP Program to overload the Operator (++) i.e. on invoking it the incrementation should happen by some random value.



## Algorithm:
1.Start the program.

2.Define a class Rep with a data member value.

3.Define a constructor to initialize value.

4.Overload the prefix ++ operator so that: i)A random number is generated. ii)That random number is added to value. iii)The new value is displayed.

5.In main(), initialize the random number generator using srand(time(0)).

6.Take input for the initial value of the object.

7.Apply the overloaded operator ++, display the incremented result, and then end the program.




## Program:
```
#include <iostream>
using namespace std;

class rep {
public:
    int a, b, c;

    void operator++() {
        a = b + c;
        cout << a;
    }
};

int main() {
    rep o;
    cin >> o.b >> o.c;
    ++o;
    return 0;
}
```


## Output:


<img width="1201" height="316" alt="566358003-50c55a88-3ad3-4865-b35a-8a0b99064480" src="https://github.com/user-attachments/assets/3df68acf-e11e-47b5-8b7a-43a67a0c08db" />



## Result:
Hence the program is executed successfully.
