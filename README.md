# Stock-Analysis: VBA_Challenge

## Overview of Project

### Purpose

   In this challenge, I had to refactor the Module 2 solution code to make the code more efficient, use less memory, improve the code, and make it easier to read and understand. Also, I measured the perfomance by running the stock analysis for both the original code and the refactored code and comparing the timer results. 
 


## Results

   > After looping through all of the data with my refactored code and analyzing the results, I saw that my refactored code executed much faster than the original. As you can see in the images, my code executed about 7 times faster than the original code. It's much faster and definitly improved. 

![Original_vs_Refactored](https://user-images.githubusercontent.com/89308251/132075919-96f1cc9b-db9a-4f65-b3b8-eb50624cae5e.png)

   > The reason my refactored code is faster is that my refactored code only loops through the data one time while the original code loops through the data 12 times, once for each ticker, because of the nested loops.

![OriginalCode_vs_RefactoredCode](https://user-images.githubusercontent.com/89308251/132076482-b60c268a-ed30-46d7-b4f8-308a85f2b903.png)



## Summary

- What are the advantages or disadvantages of refactoring code?

   > The advantages of refactoring code are better efficiency and structure, that it uses less memory, that it's easier to read and understand, and that it runs faster. 
On other hand, it takes a lot of time, can be expensive, and is very risky to manage, especially when the data is very big. It may also introduce bugs during the refactoring
process.   

- How do these pros and cons apply to refactoring the original VBA script?

   > For the pros, it did make it more efficient and definitely made it run faster. I don't know whether it is easier to read and understand because there is less
code, but the code is more dense to me.
   > For the cons, it definitely took a lot of time since I had to rewrite the whole thing. It wasn't very expensive or risky because the code and data were small.

