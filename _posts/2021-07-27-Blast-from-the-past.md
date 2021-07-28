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
published: true
---

# Table of Contents
1. [Problem](#problem)
    1. [Problem definition](#problem-definition)
    2. [Requirements](#requirements)
    3. [Limits](#Limits)
    4. [Example](#Example)
2. [Solution](#solution)


<!--- ![Painting](/assets/img/watercolor-drawing.jpg) --->

<!--- ! inline: $$f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi$$

display mode (centered):

$$f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi$$  --->

## Problem:

### Problem definition:

For a sequance of *`N`* elements, one can build **at most** *`NrX`* sequences of lenght *`1`*, *`NrY`* sequances of lenght *`2`* and *`NrZ`* sequances of lenght *`3`* that must not overlap.

### Requirements:

Find the maximum sum of subsequances with the property abovementioned.

### Limits:

* *N<=100*
* *NrX<=50*
* *NrY<=50*
* *NrZ<=50*

### Example:

Given: { 2, 3, -1, 3 }

with:

* *N=4*
* *NrX=1*
* *NrY=2*
* *NrZ=0*

The maximum sum = 8 where we have one sequance of lenght 2:=[ 2, 3] and one sequance of lenght 1:= [3]


## Solution:
