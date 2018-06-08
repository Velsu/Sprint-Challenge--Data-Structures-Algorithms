Add your answers to the Algorithms exercises here.

Exercise I:

a) O(n)
b) O(log n)
c) O(n^2)
d) O(n^2)
e) O(n^3)
f) O(n)
g) O(n)

Exercise II:

a)
const maxdiff(arr) {
let min = arr[0]
let diff = 0;

for (let i = 0; i < arr.length; i++) {
min = Math.min(min, arr[i]);
diff = Math.max(diff, arr[i] - min)
}
return diff
}

b)

Half number of floors (f/2) and check if egg still breaks. If it is half again. Repeat until egg wont break.

Exercise III:

a) O(n^2) (not sure on this one) because we need to check all elements in the array everytime.
b) O(n logn) because if pivot is always in the middle we can start determining that left part of the array will be smaller than the right part of the array.
