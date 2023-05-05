Download Link: https://assignmentchef.com/product/solved-csi-3131-assignment-4
<br>









<h1>Question 1</h1>




A page-replacement algorithm should minimize the number of page faults. We can achieve this minimization by distributing heavily used

pages evenly over all of memory, rather than having them compete for a small number of page frames. We can associate with each page frame

a counter of the number of pages associated with that frame. Then, to replace a page, we can search for the page frame with the smallest counter.

<ol>

 <li>Define a page-replacement algorithm using this basic idea. Specifically address these problems:</li>

 <li>What the initial value of the counters is ii. When counters are increased iii. When counters are decreased iv. How the page to be replaced is selected</li>

</ol>




<ol>

 <li>How many page faults occur for your algorithm for the following reference string, for four page frames?</li>

</ol>

1, 2, 3, 4, 5, 3, 4, 1, 6, 7, 8, 7, 8, 9, 7, 8, 9, 5, 4, 5, 4, 2.




<ol>

 <li>What is the minimum number of page faults for an optimal page replacement strategy for the reference string in part b with four page frames?</li>

</ol>







<h1>Question 2</h1>




Write a program that implements the FIFO and LRU page-replacement algorithms presented in this chapter.  First, generate a random page-reference string where page numbers range from 0 to 9.  Apply the random page-reference string to each algorithm, and record the number of page faults incurred by each algorithm.  Implement the replacement algorithms so that the number of page frames can vary from 1 to 7.  Assume that demand paging is used.




<h1>Question 3</h1>




The Catalan numbers are an integer sequence C<sub>n</sub> that appear in tree-enumeration problems.  The first Catalan numbers for n=1,2,3,…. Are 1, 2, 5, 14, 42, 132, …  A formula generating C<sub>n</sub> is:

C<sub>n</sub> = (2n)!/(n+1)!n!




Design 2 programs (one for the producer and one for the consumer) that communicate with shared memory on Windows or Unix/Linux.   The producer process will generate the Catalan sequence and write it to a shared memory object.  The consumer process with then read and output the sequence from shared memory.  In this instance, the producer process will be passed an integer parameter on the command line specifying the number of Catalan numbers to produce; i.e., providing 5 on the command line means the producer process will generate the first 5 Catalan numbers.








