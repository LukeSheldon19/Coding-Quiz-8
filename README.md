For the Staircase problem the time complexity is O(n^2) as time is dependent on iterating over a range of n and well as a String concatonation that has worst case time n. The space complexity is is also O(n^2), as the string ret grows in length n times with a max length of n for an iteration.


For the Alternating characters problem the time complexity is O(n^2) as it takes the first character of an n character string n times, hence n^2. The space complexity is O(n), as space is only dependent on the String of length n. For the recursive definition, the base case checks if the length of the string is less than or equal to 1. The recursive case will shrink the string by one character each time until th ebase case is reached. Other than that there is a comparison to check if two consecutive strings are the same.


