# LeetCode 506. Relative Rank

This repository contains a solution for the LeetCode problem 506. Relative Rank.

## Problem Description
You are given a list of unique scores, and you need to return a list of ranks for each athlete. The ranks are assigned as follows:
- 1st place: "Gold Medal"
- 2nd place: "Silver Medal"
- 3rd place: "Bronze Medal"
- Others: Their position in the rankings.

## Solution
The solution uses sorting to arrange the athletes in descending order of their scores and assigns ranks based on their positions in the sorted list.

## Example
For the input:
```c++
score = [10, 3, 8, 9, 4]
````
output:
````c++
["Gold Medal", "5", "Bronze Medal", "Silver Medal", "4"]
````
