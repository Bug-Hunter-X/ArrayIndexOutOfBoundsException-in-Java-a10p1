# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException`. The code attempts to access an array element beyond its valid index range.  The solution shows the correct way to iterate through an array.

## Bug Description
The original `BuggyJavaCode.java` contains a `for` loop that iterates one element past the end of the array.  This causes an `ArrayIndexOutOfBoundsException` at runtime.

## Solution
The corrected code, `CorrectedJavaCode.java`, fixes this by changing the loop condition to `i < arr.length`, ensuring that only valid indices are accessed.