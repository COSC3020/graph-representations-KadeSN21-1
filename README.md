# Graph Representations

Implement a function that converts an adjacency matrix to an adjacency list for
a directed unweighted graph using the template in `code.js`. Test your new
function; I've provided some basic testing code that uses
[jsverify](https://jsverify.github.io/) in `code.test.js`. Now, the test code
does contain the solution, so you can have a look at it if you get stuck, but
try not to peek before attempting to solve it on your own.

## Runtime Analysis

What is the runtime complexity of the conversion that you implemented? Does it
depend on the number of vertices, the number of edges, or both?

Describe your reasoning and the conclusion you've come to. Your reasoning is the
most important part. Add your answer to this markdown file.

The runtime complexity of this implementation is $O(n^2)$ with n being the vertices. Since the edges may connect vertices to create a pair of vertices, we account for this by checking for all $(n^2)$ vertex pairs, thus $O(n^2)$.

## Bonus

Implement a function to convert an adjacency list to an adjacency matrix and
analyze it as above.

Help: StackOverflow - I looked up a question regarding time complexities of variouse graphing algorithms I then used as a template to analize my implementation. I also reffered back to the course videos for help on this.
https://stackoverflow.com/questions/63666474/graph-time-complexities

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
