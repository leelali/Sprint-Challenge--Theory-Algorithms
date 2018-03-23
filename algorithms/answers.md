Exercise 1:
a): O(n)
b): best: O(1); worst: 
c): O(32 * Math.sqrt(n))
d): O(n * (Math.round(n/2)+1))
e): O(n * (n-1) * (n-2) * 10)
f): O(n)
g): best: O(1); average: O(n)



Exercise II
a): 
a.sort();
const j = a.length - 1;
const i = 0;
const max = a[j] - a[i];


b):
// test n/2 first
// if egg broke, test (n/2)/2 floor
// else, test upper half part of the n story building, test floor (n/2 + n/4)
follow the same algorithm until find the f. Running time for this solution is O(logn)



Exercise III
a): O(1). Because pivot is the first one, so O(1), also, the array is already sorted, only need to run one time. so totally is O(1)

b): O(log(n)). Because pivot is magically chosen to be the median, so O(1). Median was chosen, so every time separate less and greater perfectly, so O(log(n)); 
