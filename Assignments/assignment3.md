# Assignment 3

### At home
The following assignments are not required to be applied in the lab. You can check it yourself at home.

1. What is the value of `j's` in this program
    <section>
      <pre><code data-trim data-noescape>
      int main()
      {
          int i = 100;
          int j1 = 2 * i / 3 % 4;
          float j2 = 2 * i / 3 % 4;
          int j3 = 2.4 * i / 3 % 4;
          float j4 = 2.4 * i / 3 % 4;
          return 0;
      }
      </code></pre>
    </section>

2. Consider the following program which contains some errors. You may assume that the comments within the program accurately describe the program’s intended behavior.
      <section>
      <pre><code data-trim data-noescape>
      int main()
      {
          int n1, n2, d1; // 1
          // Get two numbers from the user
          cin << n1 << n2; // 2
          // Compute sum of the two numbers
          cout << n1 + n2 << endl; // 3
          // Compute average of the two numbers
          cout << n1+n2/2 << endl; // 4
          // Assign some variables
          d1 = d2 = 0; // 5
          // Compute a quotient
          cout << n1/d1 << endl; // 6
          // Compute a product
          n1*n2 = d1; // 7
          // Print result
          cout << d1 << "\n"; // 8
          return 0
      }
      </code></pre>
      </section>

      - For each line listed in the comments, indicate whether or not a compile-time, run-time, or logic error is present. Not all lines contain an error.

1. In each of the following expressions, suppose `a`, `b` and `c` are integer variables that have been assigned the values `a = 3, b = 2 and c =-4`. Determine the value of `y`:
    - `y = a + --b + ++c * a % c ;`
    - `y = 2 * ++b + 3 * ( a-- - c ) ;`
    - `y += a * ++b + c-- * a % c ;`
    - `y *= 4* b + 3 * ( ++a + c ) ; `   


---

### At Lab
The following assignments are required to be applied in the lab.

1. Consider the following section of C++ code:
    <section><pre><code data-trim data-noescape>
    // i, j, and k are ints
    if (i < j) {
      if (j < k)
        i = j;
      else
        j = k;
    }
    else {
      if (j > k)
        j = i;
      else
        i = k;
    }
    cout << "i = " << i << " j = " << j << " k = " << k << endl;
    </pre></code></section>

    - What will the code print if the variables i, j, and k have the following values?

      - (a) i is 3, j is 5, and k is 7
      - (b) i is 3, j is 7, and k is 5
      - (c) i is 5, j is 3, and k is 7
      - (d) i is 5, j is 7, and k is 3
      - (e) i is 7, j is 3, and k is 5
      - (f) i is 7, j is 5, and k is 3


2. Write a C++ program that displays a menu to the user with multiple options: (1) Spicy Crispy Chicken Sandwich, (2) Big Mac, and (3) Chicken McNuggets. The user has to choose only one of these three options. Based on the chosen option the program displays the price of the meal. If the user chooses an invalid option, the program displays an error message.
The program should run as follows:
    <span style="background-color:green">
    <section><pre><code data-trim data-noescape>

    Which sandwich you would like to have:
    1- Spicy Crispy Chicken Sandwich
    2- Big Mac
    3- Chicken McNuggets

    Please enter your choice: <span style="color:red">2</span>
    The price for <span style="color:blue">Big Mac</span> is <span style="color:blue">LE80</span>
    </pre></code></section>
    </span>
