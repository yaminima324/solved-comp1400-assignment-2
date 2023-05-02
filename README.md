Download Link: https://assignmentchef.com/product/solved-comp1400-assignment-2
<br>
<ol>

 <li><strong>6 </strong>(p. 51) Modify the addfrac.c program of Section 3.2 so that the user enters both fractions at the same time, separated by a plus sign. Save the program in a file named as a2 addfrac.c, and submit the file as your solution to this question.</li>

</ol>

Enter two fractions separated by a plus sign: <u>5/6+3/4 </u>The sum is 38/24

<ol start="2">

 <li><strong>1 </strong>(pp. 68-69) Show the output produced by each of the following program fragments. Assume that i, j, and k are int variables.</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="318">(a)    i = 5; j = 3; printf(“%d %d”, i / j, i % j);(b)    i = 2; j = 3;printf(“%d”, (i + 10) % j);</td>

   <td width="302">(c)    i = 7; j = 8; k = 9; printf(“%d”, (i + 10) % k / j);(d)    i = 1; j = 2; k = 3; printf(“%d”, (i + 5) % (j + 2) / k);</td>

  </tr>

 </tbody>

</table>

<ol start="3">

 <li><strong>4 </strong>(p. 69) Write a program to read an integer entered by the user and display it in octal (base 8). Save the program in a file named as a2 octal.c, and submit the file as your solution to this question.</li>

</ol>

Enter a number between 0 and 32767: <u>1953</u>

In octal, your number is: 03641

The output should be display using five digits, even if fewer digits are sufficient. <em>Hint: </em>To convert the number to octal, first divide it by 8; the remainder is the last digit of the octal number (1, in this case). Then divide the original number by 8 and repeat the process to arrived at the next-to-last digit. (printf is capable of displaying numbers in base 8 as we will see in Chapter 7, so there is actually an easier way to write this program.)

<ol start="4">

 <li><strong>3 </strong>(p. 94) The following program fragments illustrate the short-circuit behavior of logical expressions. Show the output produced by each, assuming that i, j, and k are int variables.</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="317">(a)    i = 3; j = 4; k = 5; printf(“%d “, i &lt; j || ++j &lt; k); printf(“%d %d %d”, i, j, k);(b)    i = 7; j = 8; k = 9; printf(“%d “, i – 7 &amp;&amp; j++ &lt; k); printf(“%d %d %d”, i, j, k);</td>

   <td width="280">(c)    i = 7; j = 8; k = 9; printf(“%d “, (i = j) || (j = k); printf(“%d %d %d”, i, j, k);(d)    i = 1; j = 1; k = 1;printf(“%d “, ++i || ++j &amp;&amp; ++k); printf(“%d %d %d”, i, j, k);</td>

  </tr>

 </tbody>

</table>

<ol start="5">

 <li><strong>7</strong><sup>∗ </sup>(p. 96) Create a RAPTOR flowchart that finds the largest and smallest of four integers entered by the user. Save the flowchart in a file named as a2 4integers.rap, and submit the file online as your solution to this question.</li>

</ol>

Enter 1st integer: <u>21</u>

Enter 2nd integer: <u>43</u>

Enter 3rd integer: <u>10</u>

Enter 4th integer: <u>35</u>

Largest: 43

Smallest: 10

Use as few Selection symbols as possible. <em>Hint: </em>Four Selection symbols are sufficient.

<ol start="6">

 <li><strong>7 </strong>(p. 96) Write an equivalent C program that accomplishes what the a2 4integers.rap flowchart does, with a small modification to combine the four input statement into one as below:</li>

</ol>

Enter four integers: <u>21 43 10 35</u>

Save the program in a file named as a2 4integers.c, and submit the file online as your solution to this question.