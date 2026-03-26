# Ex.No:3
# Ex.Name:Write a CPP Program to overload a function to perform sum of two integers and sum of three integers
## Date:
## Aim:
To write a CPP program to overload a function to perform the sum of two integers and the sum of three integers.



## Algorithm:
1.Start the program.
2. Define a class Addition with two overloaded functions named sum:
3. One function takes two integer arguments and returns their sum.
4. Another function takes three integer arguments and returns their sum.
5. In the main() function, create an object of the class.
6. Call both overloaded functions to compute the sum of two and three integers.
7. Display the results.
8. End the program.




## Program:
```
#include <iostream>
using namespace std;

class Sum {
public:
    void sum(int x, int y) {
        cout << "Sum of two Numbers=" << x + y << endl;
    }

    void sum(int x, int y, int z) {
        cout << "Sum of three Numbers=" << x + y + z;
    }
};

int main() {
    Sum s;
    int x, y, z;

    cin >> x >> y;
    s.sum(x, y);
    cin >> x >> y >> z;
    s.sum(x, y, z);

    return 0;
}
```


## Output:

<img width="1465" height="433" alt="566355281-0561a36e-e2ad-4614-b789-bdfea8f9fb51" src="https://github.com/user-attachments/assets/d382f4f2-3215-43fb-b6a4-6df923c9f2d3" />



## Result:
Hence the program is executed successfully.
