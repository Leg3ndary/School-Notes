## Problem A

> In how many ways is it possible to choose four distinct integers from {1;2;3;4;5;6;7}{1;2;3;4;5;6;7}, so that their sum is even?

How can we make even numbers (Unordered)? Let us consider just the case of 2 numbers, we can have an odd and an odd, or an even and an even. What about it 3 numbers? Odd, Odd, Even, or Even, Even, Even. 4?

In this case we get odd, odd, odd, odd, or odd, odd, even, even, or finally 4 evens.

However we only have 4 odd and 3 even, this means we can cross off the final 4 evens

This leaves us with 4 odd, and 3 even.

4 odd can only have 1 set of numbers, 1;3;5;7, this is because we do not care about order, and the numbers must be unique.

Finally we just consider the odd;odd;even;even case, in how many ways can we arrange these 4 odds and 3 evens?

We have 6 different solutions for the odd numbers, and 3 different solutions for the evens.

Finally, multiplying these both gives us 18 + 1 = 19 total different ways we can create an even number.

## Problem B

> Two circles, one of radius 1, the other of radius 2, intersect so that the larger circle passes through the centre of the smaller circle. Find the distance between the two points at which the circles intersect.
