Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-8-queues-stacks-files
<br>
Take a look at the three files and understand the source code. Extend the code of queue.c by implementing the enqueue() function. Follow the hints given in the slides (see Lecture 8, slide

12).

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<h1>Testcase 8.1: inputTestcase 8.1: output</h1>

aadd int: Putting 3 into queue

31 items in queue

aType a to add, d to delete, q to quit:

5add int: Putting 5 into queue a2 items in queue

7Type a to add, d to delete, q to quit: qadd int: Putting 7 into queue

3 items in queue

Type a to add, d to delete, q to quit:

Bye.

<h2><strong>Problem 8.2 </strong>Removing from the queue                                                                       (</h2>

Extend the source code of queue.c from <strong>Problem 8.1 </strong>by implementing the dequeue() function. Follow the hints given in the slides (see Lecture 8, slide 13) and consider the case of a queue underflow.

<em>You can assume that the input will be valid except the semantical possibility of reaching queue underflow. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="593">

 <tbody>

  <tr>

   <td colspan="2" width="280"><strong>Testcase 8.2: input</strong></td>

   <td rowspan="2" width="313"><strong>Testcase 8.2: output</strong>add int: Putting 3 into queue1    items in queueType a to add, d to delete, q to quit:add int: Putting 5 into queue2    items in queueType a to add, d to delete, q to quit:add int: Putting 7 into queue3    items in queueType a to add, d to delete, q to quit:Removing 3 from queue2 items in queueType a to add, d to delete, q to quit:Removing 5 from queue1 items in queueType a to add, d to delete, q to quit:Bye.</td>

  </tr>

  <tr>

   <td width="97">a 3 a 5 a 7 d d q</td>

   <td width="182"></td>

  </tr>

  <tr>

   <td width="97"><strong>Problem 8.3</strong></td>

   <td width="182"><em>Printing the queue</em></td>

   <td width="313"></td>

  </tr>

  <tr>

   <td colspan="2" width="280"></td>

   <td width="313"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Extend the source code of queue.h, queue.c and testqueue.c from <strong>Problem 8.2 </strong>by adding and implementing the additional function printq() for printing the elements of the queue separated by spaces. If you enter ’p’, then the program should print the elements of the queue. Make sure that you can print more than once.

<em>You can assume that the input will be correct. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="649">

 <tbody>

  <tr>

   <td colspan="2" width="290"><strong>Testcase 8.3: input</strong></td>

   <td rowspan="2" width="359"><strong>Testcase 8.3: output</strong>add int: Putting 3 into queue1    items in queueType a to add, d to delete, p to print, q to quit:add int: Putting 5 into queue2    items in queueType a to add, d to delete, p to print, q to quit:add int: Putting 7 into queue3    items in queueType a to add, d to delete, p to print, q to quit: content of the queue: 3 5 73 items in queueType a to add, d to delete, p to print, q to quit:Bye.</td>

  </tr>

  <tr>

   <td width="97">a 3 a 5 a 7 p q</td>

   <td width="193"></td>

  </tr>

  <tr>

   <td width="97"><strong>Problem 8.4</strong></td>

   <td colspan="2" width="551"><em>A stack for converting numbers                                                          </em></td>

  </tr>

  <tr>

   <td width="97"></td>

   <td width="193"></td>

   <td width="359"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Modify the stack implemented for <strong>Problem 7.7 </strong>such that you can use it for converting a positive decimal number stored in an unsigned int into the binary representation of the number using division by 2 and storing the remainder of the division by 2 in the stack.

Upload again all files related to this problem (i.e., stack.h, stack.c and convertingstack.c). <em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<h1>Testcase 8.4: inputTestcase 8.4: output</h1>

75The binary representation of 75 is 1001011.

<h2><strong>Problem 8.5 </strong>Read chars and write an int</h2>

Write a program which reads the first two characters from the file “chars.txt” and writes the sum of their ASCII code values as a number into “codesum.txt”. Use an editor to create the input file “chars.txt”. Your program is responsible to create the output file “codesum.txt”. <em>You can safely assume that the content of the input file will be valid.</em>

<h2><strong>Problem 8.6 </strong>Read and write doubles</h2>

Write a program which reads from the keyboard the names of two files containing two double numbers. Your program should read these two values from the two files, compute their sum, difference, product and division, and write the results on separate lines into the file “results.txt”. <em>You can safely assume that the input is valid, the two input files exist and each contains one valid double value.</em>

<table width="457">

 <tbody>

  <tr>

   <td width="457"><strong>Problem 8.7 </strong><em>Merge two files</em></td>

  </tr>

  <tr>

   <td width="457"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a program which reads the content of two files “text1.txt” and “text2.txt” line by line and merges them into another file called “merge12.txt”.

<em>You can safely assume that the input is valid.</em>

<table width="457">

 <tbody>

  <tr>

   <td width="457"><strong>Problem 8.8 </strong><em>Counting words in a file</em></td>

  </tr>

  <tr>

   <td width="457"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a program which reads the content of a file given as input and counts the number of the words in the file. It is assumed the words are separated by one or multiple of the following characters: ’ ’ ’,’ ’?’ ’!’ ’.’ ’t’ ’r’ ’
’. For testing your solution to this problem, please use:

https://grader.eecs.jacobs-university.de/courses/320112/c/words.txt https://grader.eecs.jacobs-university.de/courses/320112/c/words2.txt <em>You can assume that the content of the input file will be valid if existing.</em>

<strong>Testcase 8.8: inputTestcase 8.8: output</strong>

words.txtThe file contains 17 words.

<h1>Problem 8.9 <em>Concat n files                                                                                           </em></h1>

Write a program which reads from the standard input the value of an integer n and then the names of n files. The program should concatenate the content of the n files separated by ’
’ and write the result on the standard output and also into output.txt.

Read the input files and write the output file using the binary mode. Use a char buffer of size 64 bytes and chunks of size 1 byte when reading and the same buffer with chunks of size 64 bytes (or less if the last write and file size is not a multiply of 64) when writing