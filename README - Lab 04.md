# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?

They are able to go across the edges becuase they wrap around in similar large groups.

### Why are the names Sum of Products and Products of Sums?

They are named SOP and POS since they similar to and represent mathematical equations where in Sum of Prodcuts we have (&) | (&) which
is similar summing up mulitple products. Where in Products of Sums we have (|) & (|) which is similar to multiplying sums.

### Open the test.v file – how are we able to check that the signals match using XOR?

We check if that signals match by taking the fact that XOR outs are based on whether two inputs are both 0 or both 1 and using that to
check if it matches with the test.v file.