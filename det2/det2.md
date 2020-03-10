# det2

## Description

Computes the determinant of a 2x2 matrix stored in T, Z, Y, X.

Input

Column 1 | Column 2
---------|---------
T | Y
Z | X

Output

Column 1 | Column 2
---------|---------
\* | \*
\* | TX - YZ

(The result will be found in the X register.)

## Example

    1 ENTER 2 ENTER 3 ENTER 4
 
Column 1 | Column 2
---------|---------
1 | 3
2 | 4

    XEQ (LABEL)

Column 1 | Column 2
---------|---------
\* | \*
\* |-2

