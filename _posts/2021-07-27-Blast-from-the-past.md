---
layout: post
<!---  title: Farewell... --->
subtitle: Dynamic programming
<!--- cover-img: /assets/img/path.jpg --->
thumbnail-img: /assets/img/PD-small2.png
<!--- cover-img: /assets/img/DP.png --->
<!--- share-img: /assets/img/path.jpg --->
katex: True
tags: [computer science, algorithms, dynamic programming]
full-width: true
published: true
hidden: true
---


The book **Dynamic Programming** by *Richard Bellman* is an important, pioneering work in which a group of problems is collected together at the end of some chapters under the heading "Exercises and Research Problems," with extremely trivial questions appearing in the midst of deep, unsolved problems. It is rumored that someone once asked Dr. Bellman how to tell the exercises apart from the research problems, and he replied: `"If you can solve it, it is an exercise; otherwise it's a research problem."` — *Donald Knuth*

That being said, let's dive into the next *`exercise`*:)



# Table of Contents
1. [Problem](#problem)
    1. [Problem definition](#problem-definition)
    2. [Requirements](#requirements)
    3. [Limits](#limits)
    4. [Examples](#examples)
2. [Solution](#solution)


<!--- ![Painting](/assets/img/watercolor-drawing.jpg) --->

<!--- ! inline: $$f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi$$

display mode (centered):

$$f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi$$  --->

## Problem:

### Problem definition:

For a sequence of *`N`* elements, one can build **at most** *`NrX`* subsequences of length *`1`*, *`NrY`* subsequences of length *`2`* and *`NrZ`* subsequences of length *`3`* that *`must not`* overlap.

### Requirements:

Find the maximum sum of subsequences with the property above mentioned.

### Limits:

* *`N`<=`100`*
* *`NrX`<=`50`*
* *`NrY`<=`50`*
* *`NrZ`<=`50`*

### Examples:

#### Example 1:

Given: { 2, 3, -1, 3 }

with:

* *`N`=`4`*
* *`NrX`=`1`*
* *`NrY`=`2`*
* *`NrZ`=`0`*

The maximum `Sum = 8` where we have one subsequences of length `2 := [ 2, 3 ]` and one subsequences of lenght `1 := [ 3 ]`

#### Example 2:


## Solution:

### Pseudocode:

`Todo: Add explination...`

```
sol[N][NrX][NrY][NrZ] = 
	max(
	sol[N-i][NrX][NrY][NrZ],
	sol[N-i][NrX-1][NrY][NrZ] + value[N],
	Sol[N-i][NrX][NrY-1][NrZ] + value[N] + value[N-1],
	Sol[N-1][NrX][NrY][NrZ-1] + value[N] + value[N-1] + value[N-2] )
	
sol_final = -1;

20*20*20
for(int i = 0 ; i <= NrX ; i++)
	for( int j = 0 ; j<= NrY; j++)
		for( int k = 0; k <= NrZ; k++)
		sol_final = max ( sol_final , sol[N][i][j][k] );
```



