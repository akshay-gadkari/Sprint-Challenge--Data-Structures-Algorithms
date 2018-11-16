Add your answers to the Algorithms exercises here.

**Exercise 1**
a) O(n) as an increase in (n + 1) will cause the while loop to take (n + 1) more time

b) O(n^3) as it uses 3 loops so a linear increases in n will increase time required by n^3 times. the fourth loop is not affected by n, so we don't consider it

c) O(n) assuming bunnies is n
	input:  0 1
	output: 0 3 


**Exercise 2**
Try at floor n/2. If it doesn't break, ignore the floors below and try halfway up the remaining floors(or 3/4 n). If it does break, ignore the abive floors and try halfway up the remaining ones, or 1/4 n. this allows you to do a kind of binary search that narrows in on the correct floor _f_.
