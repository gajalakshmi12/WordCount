Java Hadoop has been used in my solution. The map method has been changed to convert text to String Tokens and store them in a String Array. I've since iterated through the array and added five strings as a single chunk for each iteration. After finishing a string of five words, I check and end the inner loop using a counter variable. This is used as an input by the reduce function.

Problems encountered :
1. Boundary Conditions (resolved by for loop)
2. White spaces was missed initially. I have appended spaces before converting to String.
