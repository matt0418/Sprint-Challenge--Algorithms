## Exercise I

a: The single while loop makes is the main determiner, makes the snippet O(n)

b: Four nested for loops means you can roughly assess this to be O(n^4)

c: The recursion simplifies down to 2(number of bunnies), so O(n) is correct

##Exercise II

We can apply a binary search to determine the floor that will break the egg. 
Start at the midpoint and drop the egg. If it breaks take the midpoint of the lower half and drop the egg and see if it breaks. And continue until it no longer breaks. Once there, take the midpoint of the higher half and drop an egg. Continue with this pattern until only one floor remains.

Though, taking all basic assumptions of eggs and buildings into account, one can realistically assume that the answer would be the zeroeth floor, as an egg dropped from a first floor window will almost certainly break  ¯\_(ツ)_/¯
