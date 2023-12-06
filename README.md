# CSCI160-CQ8-Optional-
Alternating Characters:
    * Time Complexity: O(n)
        - The worse case of the problem is when the function call all of the
          character once in the string, which is O(n)
    * Space Complexity: O(n)
        - It create a substring while running through each recursive call. Also since           there are only n characters, the worse case for space complexity is O(n)

The recursive definition of the problem is reducing the problem ar each step by considering the first two characters of the string. increment a counter and call the function recursively on the substring from the second character. If it is different, you call the function recursively without incrementing the counters. The base case is used when the string reduced to length 0 or 1 
        
Staircase:
   * Time Complexity: O(n^2)
         - There are two main loop that iterate through n items; therefore, the time
           complexity is O(n^2)
   * Space Complexity: O(1)
        - There are constant numbers of variables and the size doesn't change 
