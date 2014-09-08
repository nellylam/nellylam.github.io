---

title: Week 8 - BigO Notation
layout: post

---

BigO Notation, also known as BigOh Notation, is used to measure the complexity of an algorithm in computer science.

In other words, it is used to describe the time that it takes to execute an algorithm if scaled to the worst case scenario. For example if the algorithm were to be ran 1 million times instead of once. How much longer will it take?

Some things to know about BigO Notation:
- It is also used in mathematics, but we will focus on how it’s used in computer science and programming.
- It measures the worst-case scenario, not the average nor the best case.

BigO Basics
These are the notations for different complexities and what it means:

O(1) - The algorithm will always finish in the same amount of time no matter how many times it is ran.

O(n) - This represents a linear relationship. The larger the input data, the longer it would take, proportionally.

O(n<sup>2</sup>) - An increase of twice the size of a data set would quadruple the size of the algorithm.

O(2<sup>N</sup>) - An increase of one step will double the size of the algorithm. This is exponential and an grow really quickly.

O(n!) - factorial or combinatorial complexity can also grow extremely fast. A good example would be the [traveling salesman problem](http://en.wikipedia.org/wiki/Travelling_salesman_problem).

O(log N) - This describes a very common algorithm in programming, called the “binary search.” There’s actually a really good example for this: The telephone book. To find a name in the telephone book, you would open it in the middle, evaluate if the name is in the first or second half of the book, ignore the half that does not apply, essentially halving the size of the book with every iteration. So at first, an increase in data input will increase the performance of the algorithm significantly, but it eventually levels off.

What they look like:
![Big O Graph]({{ site.baseurl }}/images/bigograph.png)
-BigOCheatsheet.com

This was just a basic overview of Big O Notation. I hope this will hold you over so that at least you can understand some idea of Big O Notation when you see it.

![The Traveling Salesman Problem]({{ site.baseurl }}/images/traveling_salesman.png)
-snatched from [xkcd.com](http://xkcd.com/399/)



Resources:
[Plain English Explanation of Big O](http://stackoverflow.com/questions/487258/plain-english-explanation-of-big-o) - Stack Overflow
[BigO Cheatsheet](http://bigocheatsheet.com/)
[Big O Notation](http://en.wikipedia.org/wiki/Big_O_notation) - Wikipedia
[Time Complexity](http://en.wikipedia.org/wiki/Time_complexity) - Wikipedia