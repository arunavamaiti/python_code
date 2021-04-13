# python_code
Q1.
python
There is a large pile of socks that must be paired by color. Given an array of integers representing the color of each sock, determine how many pairs of socks with matching colors there are.

Example
There is one pair of color  and one of color . There are three odd socks left, one of each color. The number of pairs is .

int n: the number of socks in the pile
int ar[n]: the colors of each sock
Returns

int: the number of pairs
Input Format

The first line contains an integer , the number of socks represented in .
The second line contains  space-separated integers, , the colors of the socks in the pile.

Constraints

 where 
Sample Input

STDIN                       Function
-----                       --------
9                           n = 9
10 20 20 10 10 30 50 10 20  ar = [10, 20, 20, 10, 10, 30, 50, 10, 20]
Sample Output

3
Explanation

There are three pairs of socks.

![q1.image.png](images/relative/path/q1.image.png)


Q2:
Let’s learn about list comprehensions! You are given three integers X, Y and Z representing the dimensions of a cuboid along with an integer . You have to print a list of all possible coordinates given by (i, j, k) on a 3D grid where the sum of i+j+k is not equal to N . Here, 0<=i<=X; 0<=j<=Y; 0<=k<=Z.

Input Format

Four integers X,Y,Z and N each on four separate lines, respectively.

Constraints

Print the list in lexicographic increasing order.

Sample Input

1

1

1

2

Sample Output

[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0], [1, 1, 1]]

Solution:

First we have read all the values x, y, z, n input from user  and convert those values to integer. Then we use list comprehension.

Here we have applied a list comprehension inside the print function. It sum up to, for all the value of i in x+1, for all the value of j in y+1, for all the value of k in z+1, if the value of i+j+k is not equal to n, append the value of [ i , j, k ] in list. After all the loop have run their course, the list is print out.
