---

title: Week 8 - BigO Notation
layout: post

---

<p class='articleheadings'>What is BigO Notation, and what does it have to do with programming?</p>
<p>BigO Notation (or BigOh Notation) is used to measure the complexity of an algorithm in computer science.</p>

<p>In other words, it is used to describe the time that it takes to execute an algorithm if scaled to the worst case scenario. For example if we wanted to add <em class='code'>23463455424 + 23434457958</em> instead of <em class='code'>1 + 1</em>, how much longer will it take?</p>

<p class='articleheadings'>Some things to know about BigO Notation:</p>
<p>
	<ul>
		<li>It is also used in mathematics, but we will focus on how it’s used in computer science and programming.</li>
		<li>It measures the worst-case scenario, not the average nor the best case.</li>
		<li>- It only cares about the most significant part of the complexity. For example, n<sup>2</sup> + 2n can be simplified to n<sup>2</sup>.</li>
	</ul>
</p>
<p>BigO Basics
These are the notations for different complexities and what it means:</p>

<p><em class='subheading'>O(1)</em> - The algorithm will always finish in the same amount of time no matter how many times it is ran.</p>

<p><em class='subheading'>O(n)</em> - This represents a linear relationship. The larger the input data, the longer it would take, proportionally.</p>

<p><em class='subheading'>O(n<sup>2</sup>)</em> - An increase of twice the size of a data set would quadruple the size of the algorithm.</p>

<p><em class='subheading'>O(2<sup>N</sup>)</em> - An increase of one step will double the size of the algorithm. This is exponential and an grow really quickly.</p>

<p><em class='subheading'>O(n!)</em> - factorial or combinatorial complexity can also grow extremely fast. A good example would be the <a href="http://en.wikipedia.org/wiki/Travelling_salesman_problem">traveling salesman problem</a>.</p>

<p><em class='subheading'>O(log N)</em> - This describes a very common algorithm in programming, called the “binary search.” There’s actually a really good example for this: The telephone book. To find a name in the telephone book, you would open it in the middle, evaluate if the name is in the first or second half of the book, ignore the half that does not apply, essentially halving the size of the book with every iteration. So at first, an increase in data input will increase the performance of the algorithm significantly, but it eventually levels off.</p>

<p>What they look like:</p>
<img src="{{ site.baseurl }}/images/bigograph.png" alt="Big O Graph" />
<figcaption>-BigOCheatsheet.com</figcaption>

<p>This was just a basic overview of Big O Notation. I hope this will hold you over so that at least you can understand some idea of Big O Notation when you see it.</p>

<img src="{{ site.baseurl }}/images/traveling_salesman.png" alt="The Traveling Salesman Problem" />
<figcaption>-snatched from <a href="http://xkcd.com/399/">xkcd.com</a></figcaption>

<p>Resources:
<ul>
	<li><a href="http://stackoverflow.com/questions/487258/plain-english-explanation-of-big-o">Plain English Explanation of Big O</a> - Stack Overflow</li>
	<li><a href="http://bigocheatsheet.com/">BigO Cheatsheet</a></li>
	<li><a href="http://en.wikipedia.org/wiki/Big_O_notation">Big O Notation</a> - Wikipedia</li>
	<li><a href="http://en.wikipedia.org/wiki/Time_complexity">Time Complexity</a> - Wikipedia</li>
</ul></p>