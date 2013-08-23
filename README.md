MergeSort Algorithm
===================

About
------------
MergeSort is an O(n * log n) comparison-based sorting algorithm.
MergeSort is a divide and conquer algorithm that was invented by John von Neumann in 1945.

Running code examples
------------
**C** implementation:

You should compile the source file first.

    cd C/
    gcc -o MergeSort MergeSort.c (Linux)
    ./MergeSort ../in/inputBig.txt (Linux)
    
    compile with Visual Studio | MinGW | DevC++ (Windows)
    MergeSort.exe ../in/inputBig.txt (Windows)

**Java** implementation:

Contains also a JUnit test file.

Used java 1.6.0_33, junit 4.10 to compile source files.

    cd Java/
    java MergeSort ../in/inputBig.txt (Windows & Linux)
    java -cp "<path_to_junit_4.x_jar_file>;./" org.junit.runner.JUnitCore MergeSortTest (Windows)
    java -cp "<path_to_junit_4.x_jar_file>:./" org.junit.runner.JUnitCore MergeSortTest (Linux)

To compile yourself the source files:

    cd Java/
    javac MergeSort.java (Windows & Linux)
    javac -cp "<path_to_junit_4.x_jar_file>;./" MergeSortTest.java (Windows)
    javac -cp "<path_to_junit_4.x_jar_file>:./" MergeSortTest.java (Linux)

For the input files in *in/* folder the expected results are: the sorted vectors.
