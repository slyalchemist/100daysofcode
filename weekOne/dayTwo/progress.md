# Daily Progress

## Day 2 - [9/24/2024]

### Today's Progress

- Solved the Weekly Challenge "String Reversal"


### Thoughts
- Challenge was considerably harder than I thought, I definitely need to do some more review on computer logic.
- I went through several iterations of the code (I probably should have saved earlier submissions) but don't fully understand why they weren't correct. 
    - My first several iterations were incorrect because I was creating a new string instead of mutating the original string.
    - My next iterations were incorrect because the temporary string I created was becoming mutated as the original string mutated.
    - To actually solve the problem, I needed to access the string from two pointers, at opposite ends of the string. Thus there would be no element lost and the string would successfully reverse.
- I did look at other solutions for guidance but eventually got it figured out on my own - though I did it in perhaps a more convoluted way using a `for` loop while most others used a `while` loop. 


### Link to Work

[LeetCode 'String Reversal' Submission](https://leetcode.com/problems/reverse-string/submissions/1401397438)

### Next Steps

- I still need to further fill out my repository structure
- I also need to make the file with my study/review topics
- Tomorrow I might take back up The Odin Project Lessons