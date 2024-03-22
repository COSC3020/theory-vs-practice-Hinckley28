[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/FgMJElkj)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.


1. One reason asymptotic analysis may be misleading is that it does not take into account the type of data that algorithms are being used for. Data such as integers are much easier for algorithms to process than things like pictures, strings, or videos. These things could ultimately result in a runtime much greater than expected. Another reason asymptotic analysis may be misleading is that it can assume that we do not have any knowledge of the data. For example, we may collect data that is already sorted or close to sorted. So if we want to choose a sorting algorithm to sort that data, we may look at the average case run times for all sorting algorithms and choose the fastest one. But if we know that the data is already sorted or close to sorted, we could choose an algorithm like insertion sort which has one of the worst average case run times but one of the best best case run times. Finally, a third reason why asymptotic analysis can be misleading is that it ignores hardware factors. The run time for certain algorithms may be faster, but require more memory from the device. This could cause problems if you want to work with a faster algorithm on a device that does not have enough memory to support that algorithm.

2. The time compelexity could only be expected to be log(10000) if the tree is balanced, but there is no way to know the exact time it would take to find the same element. It would depend on many different factors such as hardware and the data that was put into the tree. 

3. One reason this could have happened is because the first input size is small enough for the data to be stored inside the computers RAM, whereas the second input size has to store some of the data in the disk drive, causing the computer to have to switch from the RAM to the disk drive which is much slower. Another reason may be that the size of the data that was added to the new, larger tree, is larger than the data in the smaller tree which takes the computer a lot longer to process. For example, the data in the first tree was all made up of integers. The data in the second tree is all strings, which are harder to compare than integers. A third reason this could happen is because the search function for the element in the tree is written enefficiently and calls unnecessary function calls or iterations. This increases the search function time complexity from log n to something like n^2 or greater. 
