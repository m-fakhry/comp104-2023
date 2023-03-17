# Assignment 4

1. Write and run a program that reads a six-digit integer and prints the sum of its six digits. Use the quotient operator / and the remainder operator % to extract the digits from the integer. For example, if n is the integer 876,543, then n/1000%10 is its thousands digit 6.

2. Consider the following section of C++ code:
    <section><pre><code data-trim data-noescape>

    #include <iostream>
    using namespace std;

    int main() {

          int input;
          cin >> input;
          if (input < 10) {
            if (input != 5)
              cout << "wow ";
            else
              input++;
          } else {
            if (input == 17)
              input += 10;
            else
              cout << "whoa ";
          }
          cout << input << endl;
    }

    </pre></code></section>

      - What will the program print if the user provides the following input?

        - (a) 3
        - (b) 21
        - (c) 5
        - (d) 17
        - (e) -5