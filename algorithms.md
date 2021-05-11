# A brief introduction to algorithms

## What are algorithms?

Sounds like a really scary word to us, yet, what are algorithms?
Algorithms are nothing more than a step-by-step solution to solve a given problem, it allows the program to generate an output starting from a given input.

![Algorithms](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/time-and-space-complexity-analysis-of-algorithm-flow-of-algorithm-3df63a24cb959397.png)

But algorithms are not exclusively related to computers. We can consider as an algorithm even a cooking recipe.
However, to describe an algorithm to a computer we must be **precise** and there must **not** be any ambiguity.

## What should be considered when writing an algorithm?

### Correctness

First of all, the algorithm must be **correct**.
But let's take an example, let's say that we want to search for a word in an English dictionary, we will go through the pages one by one until we find the right word. 
We can use [pseudocode](https://en.wikipedia.org/wiki/Pseudocode) to describe our algorithm:
```
for every page in the dictionary
	if the word we are looking for is on the page
		check the meaning of the word
	else
		continue searching
```

### Bugs

But what happens if the word is not in the dictionary?
We get a bug, an error in our program which, for example, can result in a crash. 
It often happens because of some edge cases that were not handled by the programmer. As in this case where the word is not in the dictionary.

So, let's correct our algorithm:
```
for every page in the dictionary
	if the word we are looking for is on the page
		check the meaning of the word
	else
		continue searching
if word not in the dictionary
	buy another dictionary
```

### Efficiency

Well, now the algorithm is certainly correct, but it's EXTREMELY slow. It can take ages to find a single word.
So, how could you have guessed, another thing to consider when writing an algorithm is the **efficiency**.

So, since our algorithm is so slow, we can maybe decide to flip through the pages two by two, so our algorithm is two times faster than before.
But, is it correct?

Well... The reply is NO.
What happens if we accidentally skip the word? This leads to another **bug**, so the solution isn't acceptable.

But what we do when we search for a word in a dictionary?
We start from the middle, and we check if the word is after or before the current page, halving the problem every time.

This is the pseudocode for the current algorithm:
```
while there more than 1 pages left
	if the word is on the page
		check the meaning of the word
		stop searching
	else, if the word is in the left half of the dictionary
		open the dictionary in the middle of the left half
	else, if the word is in the right half of the dictionary
		open the dictionary in the middle of the right half
	else
		buy another dictionary
```

Amazing! Now we have a correct and also very efficient algorithm.

## Time complexity

But, how do we describe the efficiency of the algorithm?

We use what we call the *Big-O notation*. 
We won't go too much in-depth in this article but, if you want [here](https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/) is a great article.

This is the time complexity of our algorithms:
![time complexity](https://cs50.harvard.edu/college/2021/spring/notes/0/running_time.png)
Note: *`n` is the size of the input (in this case the number of the dictionary pages)*

Let's analyze the graph:
 1. The red line, this was the first algorithm (the one where we go through the pages one by one). It's what we call a linear time.
 2. The yellow line is the second algorithm, the time complexity is similar to the first one, but it's halved since we scroll two pages at a time.
 3. The third one (green line) as you can see is not a straight line, this is because it's a **logarithmic** time complexity, the time it takes to solve the problem decreases as we progress.

## Thanks for your attention

We have got to the end!
Now you have a basic understanding of algorithms and time complexity, and you are ready to code!

---

Happy debugging,

*Kappa* | Engrafa team
