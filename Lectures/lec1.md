# Lecture 1

## Notes

- What is a programming language
- What is a computer program
- Basic form of C++ program
- We started with the very basic (incomplete) form of a C++ program
<section>
  <pre><code data-trim data-noescape>
    int  main( ) {
        …;
        …;
    }
  </code></pre>
</section>

- We then started to add additional commands to make the program valid
<section>
  <pre><code data-trim data-noescape>

    int  main( ) {
        …;
        …;
        return 0;
    }
  </code></pre>
</section>

- We explained what a library is, and give an example of `iostream` library.
<section>
  <pre><code data-trim data-noescape>
    #include < iostream >
    int  main( ) {
        …;
        …;
        return 0;
    }
  </code></pre>
</section>

- We explained the `cout` statement
<section>
  <pre><code data-trim data-noescape>
    #include < iostream >
    int  main( ) {
        cout<<2+3;
        return 0;
    }
  </code></pre>
</section>

- and gave two forms of `cout` to print either a string or expression. So, the difference between `cout<<"2+3=";`  and `   cout<<2+3;`

- then, how to merge multiple `cout` statements in one statement. For example, `cout<<"2+3="<<2+3;`

- finally, the delimiter `\n`.
