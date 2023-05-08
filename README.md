Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-7-brutal-force-method-for-assignment-problems
<br>
<strong>Brutal Force Method for Assignment Problems (2020) </strong>

Solve a Job Assignment (or Assembly Sequencing, or TSP problem) problem by using brutal force method to enumerate all possible solutions and compute their objective values. Report the best solution and objective value.

<ol>

 <li>Read the input files from a text file with the format given at the end of this document.</li>

 <li>Loop through each possible assignment, evaluated its setup time, and display the content of the assignment on the UI.</li>

 <li>Recursive function is required in your code to systematically constitute all compositions of the jobs in difference sequences.</li>

</ol>

<table width="223">

 <tbody>

  <tr>

   <td width="127">7</td>

   <td width="96"><em>n </em></td>

  </tr>

  <tr>

   <td width="127">14 5 8 7 6 10 82 12 6 5 9 4 37 8 3 9 8 11 42 4 6 10 7 9 35 8 10 14 3 5 94 8 7 6 10 8 73 5 7 8 6 4 7</td>

   <td width="96"><em>c</em>00~<em>c</em>0(n-1) <em>c</em>10~<em>c</em>1(n-1) <em>c</em>20~<em>c</em>2(n-1) <em>c</em>30~<em>c</em>3(n-1) <em>c</em>40~<em>c</em>4(n-1) <em>c</em>50~<em>c</em>5(n-1) <em>c</em>60~<em>c</em>6(n-1)</td>

  </tr>

 </tbody>

</table>

<ol start="4">

 <li>In addition, report the best solution and the minimal setup time.</li>

</ol>

<strong>Job Assignment Problem: </strong>

A company has <em>n</em> machines and <em>n</em> jobs to be processed. Each job must be assigned with exactly one machine to process the job. The setup time for a machine to process a job is dependent on the job and the machine. Assume that<strong>C</strong><sub>=</sub><em>C<sub>i</sub></em><sub>, <em>j </em></sub>, <em>C<sub>i</sub></em><sub>, <em>j </em></sub>is the setup time of machine <em>j</em> to process job <em>i</em>. The company wants to minimize the total setup time. Let a solution<strong>x</strong>=<em>x</em><sub>0</sub>,<em>x</em><sub>1</sub><sup>,</sup>L,<em>x</em><em><sub>n</sub></em><sub>−1</sub>, <em>x<sub>j </sub></em>0,1,L,<em>n</em>−1<em>x<sub>j </sub></em><em>x<sub>j</sub></em><sub> </sub>such that job

<em>n</em>−1

<em>x<sub>j </sub></em>is assigned to machine <em>j</em>. Therefore, the total setup time of the given solution <strong>x </strong>isT=<em>C<sub>x </sub></em><em><sub>j </sub></em>, <em><sub>j </sub></em>, which is to

<em>j</em>=0

be minimized.

The benchmarks of job assignment problems are defined files with file extension “aop”. Sample file: