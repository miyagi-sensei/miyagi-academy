# s193 - Alice's Housekeeper
## Problem Statement
- Convert a string of length `N` into one that has no "consecutive repeats" by replacing the minimum number of letters.
- `K` letters are allowed for the string
- If impossible, print "Impossible"
- 1 ≤ `N` ≤ 10<sup>6</sup>
- 2 ≤ `K` ≤ 26

## Analysis of test inputs
1. When there are "repeats", you can just replace 1 of the 2 letters to resolve the repeats. But how do you determine with what letters do you replace them?<br>
```
8 26
abzzabzz
```
