# comp2160-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP2160 Assignment 3 Solved](https://www.ankitcodinghub.com/product/comp2160-assignment-3-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101065&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2160 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<header id="title-block-header">
<h1 class="title"></h1>
</header>
<h1 id="description">Description</h1>
In assignment 3 we’re going to apply what we’ve learned about interfaces, testing, and multi-file compilation.

<h2 id="notes">Notes</h2>
<ul>
<li>Read the&nbsp;<em>entire</em>&nbsp;assignment document before starting.</li>
<li>Your programs must run correctly both with assertions enabled and disabled (when compiled with and without the&nbsp;<code>-DNDEBUG</code>&nbsp;option).</li>
<li>Please be sure to follow the&nbsp;<a href="/d2l/le/content/518960/viewContent/3112728/View" target="_blank" rel="noopener">programming standards</a>; not doing so will result in a loss of marks.</li>
<li>Remember to complete the Honesty Declaration Checklist (you will not receive scores for your assignments until the checklist is completed).</li>
<li>All submitted assignments will be scanned with automated software to monitor for academic integrity violations.</li>
<li>Your assignment code must be handed in electronically. See the Submitting your assignment section below for more information.</li>
<li>Late assignments are not accepted. The due date is enforced electronically.</li>
</ul>
<h1 id="objectives">Objectives</h1>
<ul>
<li>Designing interfaces and building implementations.</li>
<li>Multi-file compilation.</li>
<li>Testing.</li>
</ul>
<h1 id="question-1-container">Question 1: Container</h1>
For question 1, you’re going to write an interface for an abstract data type (a “<a href="https://en.wikipedia.org/wiki/Container_(abstract_data_type)" target="_blank" rel="noopener">Container</a>”), and you’re going to provide an implementation of that ADT with a linked list.

<h2 id="the-interface">The interface</h2>
First, you should build an interface for the container ADT. Your container will store&nbsp;<em>strings</em>&nbsp;(as&nbsp;<code>char*</code>).

We’ll give you the names of the functions below, but&nbsp;<strong>you</strong>&nbsp;must write complete prototypes for your interface. Choosing the return types and parameter types is your responsibility.

Your interface should contain the&nbsp;<em>minimal</em>&nbsp;amount of information required for someone to use your implementation in their code.

<h3 id="functions">Functions</h3>
Your interface should be implemented as&nbsp;<code>container.h</code>&nbsp;with the following function&nbsp;<em>names</em>:

<h4 id="creating-and-destroying">Creating and destroying:</h4>
<ul>
<li><code>createContainer</code>&nbsp;<ins>(Create a new instance of the container)</ins></li>
<li><code>destroyContainer</code>&nbsp;<ins>(Destroy the container and its contents)</ins></li>
</ul>
<h4 id="manipulation">Manipulation:</h4>
<ul>
<li><code>insert</code>&nbsp;<ins>(Insert an item into the container)</ins></li>
<li><code>delete</code>&nbsp;<ins>(Remove the specified item from the container, only one if there are multiple)</ins></li>
<li><code>clear</code>&nbsp;<ins>(Remove&nbsp;<em>all</em>&nbsp;items from the container)</ins></li>
</ul>
<h4 id="iterating-and-searching">Iterating and searching:</h4>
<ul>
<li><code>firstItem</code>&nbsp;<ins>(Start iterating over items in the container)</ins></li>
<li><code>nextItem</code>&nbsp;<ins>(Continue iterating over items in the container)</ins></li>
<li><code>contains</code>&nbsp;<ins>(Does the container contain this item?)</ins></li>
<li><code>size</code>&nbsp;<ins>(how many items are in the container?)</ins></li>
</ul>
<h2 id="the-implementation">The implementation</h2>
Once you’ve got an interface, create an implementation for the container by implementing a&nbsp;<strong>linked list</strong>&nbsp;of strings. Your implementation should define the data structure, and implement all of the functions declared as prototypes in the interface.

Your linked list implementation must apply the principles of design by contract. In particular, you should be implementing a function invariant on the linked list.

Your implementation should be implemented as&nbsp;<code>container.c</code>.

<h2 id="the-tests">The tests</h2>
Finally, you should build an automated test suite for your container implementation.

Your test suite should be implemented in a file called&nbsp;<code>main.c</code>, and you should be sure to test all functions in the file with both general case and edge case test data.

Tests should be organized appropriately into their own functions.

Your test suite should report:

<ol type="1">
<li>Progress: a statement about what the test is testing (i.e., “searching for X”)</li>
<li>Success: a statement about whether or not the test succeeded (i.e., “FAILED: expected to find X, but could not find it.” or “SUCCESS: expected to find X and found it.”)</li>
<li>Summary: a summary of the number of tests run, the number of tests passed, and the number of tests failed.</li>
</ol>
You should refer back to the Levenshtein implementation in Assignment 1 to get an idea of what a testing suite that matches this description looks like.

<h2 id="building">Building</h2>
Your solution for question 1 must include a&nbsp;<code>Makefile</code>. The grader should only have to type the command&nbsp;<code>make</code>&nbsp;in your directory to build your assignment.

<h1 id="question-2-black-box-testing">Question 2: Black-box testing</h1>
You have been provided with an implementation of a&nbsp;<a href="https://en.wikipedia.org/wiki/Set_(abstract_data_type)" target="_blank" rel="noopener">set ADT</a>&nbsp;developed by a third-party. The implementation consists of a header file&nbsp;<a href="/d2l/le/content/518960/viewContent/3165703/View" target="_blank" rel="noopener"><code>set.h</code></a>&nbsp;that defines the interface and a compiled object file with the implementation.

Your job is to verify that the third-party developer is not a terrible programmer (hint: they&nbsp;<em>aren’t</em>&nbsp;terrible, they’re&nbsp;<strong>really</strong>&nbsp;terrible).

You should implement a complete test suite for the set ADT and provide a report (in a&nbsp;<a href="https://guides.github.com/features/mastering-markdown/" target="_blank" rel="noopener">Markdown-formatted</a>&nbsp;<code>README</code>&nbsp;file) explaining what is broken with the implementation of the set that this&nbsp;<strong>really</strong>,&nbsp;<em>really</em>&nbsp;terrible programmer has given to you.

You should use the testing suite you built in question 1 as a basis for the testing suite you build here.

<h2 id="the-first-set">The first set</h2>
You have been provided with&nbsp;<strong>one</strong>&nbsp;implementation of the set by a&nbsp;<em>competent</em>&nbsp;programmer. The implementation is in a file called&nbsp;<a href="/d2l/le/content/518960/viewContent/3165705/View" target="_blank" rel="noopener"><code>set.o</code></a>&nbsp;that has been compiled on aviary (Linux). The first implementation that you’re being provided with is 100% correct – none of the functions in this file are implemented incorrectly, there are no bugs in this implementation.

<h2 id="the-tests-1">The tests</h2>
Your job is to write a complete test suite for the implementation of a set.

Your test suite should be implemented in a file called&nbsp;<code>main.c</code>, and you should be sure to test all functions in the file with both general case and edge case test data. Also note that there’s a function called&nbsp;<code>validateMemUse()</code>&nbsp;that can be used to verify that all instances of&nbsp;<code>Set</code>&nbsp;that were created have been destroyed – your test suite should use this function to check for memory leaks.

Tests should be organized appropriately into their own functions.

Your test suite should report:

<ol type="1">
<li>Progress: a statement about what the test is testing (i.e., “searching for X”)</li>
<li>Success: a statement about whether or not the test succeeded (i.e., “FAILED: expected to find X, but could not find it.” or “SUCCESS: expected to find X and found it.”)</li>
<li>Summary: a summary of the number of tests run, the number of tests passed, and the number of tests failed.</li>
</ol>
For the set implementation that’s provided above, all of the tests you write&nbsp;<strong>will pass</strong>.

<h2 id="the-other-sets">The&nbsp;<em>other</em>&nbsp;sets</h2>
Closer to the due date, we will provide you with 5 more implementations of a set that implement the same interface. You will use the test suite that you wrote for the&nbsp;<em>correct</em>&nbsp;implementation of a set to determine what (if anything) is wrong with each of the set implementations that you’re provided with.

You must write a brief analysis for each file in a file called&nbsp;<code>README.md</code>.&nbsp;<code>README.md</code>&nbsp;should be a&nbsp;<a href="https://guides.github.com/features/mastering-markdown/" target="_blank" rel="noopener">Markdown-formatted</a>&nbsp;file (use headings!).

While the code we will provide to you is&nbsp;<em>buggy</em>, it&nbsp;<strong>will not crash</strong>. If you receive any error messages (segmentation fault, abort, bus error), the crash is happening in&nbsp;<strong>your</strong>&nbsp;code. When this happens, your strategy should be to re-read the comments in the set interface to better understand what each function does/requires. If you still can’t figure out why your tests are crashing, you should pull out your debugger and debug your code.

<h1 id="submitting-your-assignment">Submitting your assignment</h1>
Create a directory called&nbsp;<code>comp2160-a3-&lt;yourlastname&gt;-&lt;yourstudentid&gt;</code>. Within that directory, create a directory for each of Q1 and Q2, where you will put your respective files for each problem.

Then run the command:

<div id="cb1" class="sourceCode">
<pre class="sourceCode bash"><code class="sourceCode bash"><span id="cb1-1"><span class="ex">handin</span> 2160 A3 comp2160-a3-<span class="op">&lt;</span>yourlastname<span class="op">&gt;</span>-<span class="op">&lt;</span>yourstudentid<span class="op">&gt;</span></span></code></pre>
</div>
<ul>
<li>You may optionally include a&nbsp;<code>README</code>&nbsp;file in the root of your directory that explains anything unusual about compiling or running your programs.</li>
<li>You may resubmit your assignment as many times as you want, but&nbsp;<strong>only the latest</strong>&nbsp;submission will be kept.</li>
<li>We only accept homework submissions via&nbsp;<code>handin</code>. Please&nbsp;<strong>do not</strong>&nbsp;e-mail your homework to the instructor or TAs – it will be ignored.</li>
<li>You&nbsp;<strong>must</strong>&nbsp;submit an Honesty Declaration (digitally on UM Learn). Assignments submitted without a corresponding Honesty Declaration&nbsp;<strong>will not be graded</strong>.</li>
<li>We reserve the right to refuse to grade the homework, or to deduct marks if these instructions are not followed.</li>
</ul>
<h1 id="evaluation">Evaluation</h1>
Your assignment is worth 30 points, 15 points × 2.

Note that your code&nbsp;<strong>must</strong>&nbsp;compile – no part marks will be given for code that does not compile.

Note further that your code&nbsp;<strong>must</strong>&nbsp;compile with&nbsp;<code>make</code>. Graders&nbsp;<strong>will not</strong>&nbsp;manually compile any code by running&nbsp;<code>clang</code>&nbsp;for this assignment,&nbsp;<em>even if</em>&nbsp;you write instructions in the&nbsp;<code>README</code>.

<h2 id="warnings">Warnings</h2>
The code you write should compile with&nbsp;<code>clang -Wall</code>&nbsp;<em>without</em>&nbsp;any warnings. A 1 point penalty will be applied to your score (before multiplication) for&nbsp;<em>each</em>&nbsp;warning that is emitted by the compiler.

<h2 id="question-1">Question 1</h2>
<table>
<colgroup>
<col>
<col></colgroup>
<thead>
<tr class="header">
<th>Level</th>
<th>Criteria</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>0</td>
<td>
<ul>
<li>No submission for Q1 is made, or</li>
<li>The submitted code does not compile on&nbsp;<code>aviary.cs.umanitoba.ca</code>&nbsp;with the expected compilation commands.</li>
</ul>
<div id="cb2" class="sourceCode">
<pre class="sourceCode bash"><code class="sourceCode bash"><span id="cb2-1"><span class="fu">make</span></span></code></pre>
</div>
</td>
</tr>
<tr class="even">
<td>1</td>
<td>
<ul>
<li>Code is submitted for the problem, and the code compiles.</li>
<li>The compiled code crashes, does not run, or does not complete in a reasonable amount of time (&lt; 5 seconds).</li>
<li>The C code is of high quality, following the standards described in the&nbsp;<a href="/d2l/le/content/518960/viewContent/3112728/View" target="_blank" rel="noopener">programming standards</a>&nbsp;document.</li>
</ul>
</td>
</tr>
<tr class="odd">
<td>2</td>
<td>
<ul>
<li>The criteria for 1 is met.</li>
<li>The interface (<code>.h</code>&nbsp;file) is complete.</li>
<li>The interface contains the&nbsp;<em>minimal</em>&nbsp;amount of information needed to use the implementation.</li>
</ul>
</td>
</tr>
<tr class="even">
<td>3</td>
<td>
<ul>
<li>The criteria for 2 is met.</li>
<li>The&nbsp;<em>creation and destruction</em>&nbsp;functions are defined in the implementation.</li>
<li>DbC principles are applied to the creation and destruction function implementations.</li>
<li>Tests have been written that adequately test the creation and destruction functions.</li>
</ul>
</td>
</tr>
<tr class="odd">
<td>4</td>
<td>
<ul>
<li>The criteria for 3 is met.</li>
<li>The&nbsp;<em>manipulation</em>&nbsp;functions are defined in the implementation.</li>
<li>DbC principles are applied to the manipulation functions.</li>
<li>Tests have been written that adequately test the manipulation functions.</li>
</ul>
</td>
</tr>
<tr class="even">
<td>5</td>
<td>
<ul>
<li>The criteria for 4 is met.</li>
<li>The&nbsp;<em>iterating and searching</em>&nbsp;functions are defined in the implementation.</li>
<li>DbC principles have been applied to the iterating and searching function implementations.</li>
<li>Tests have been written that adequately test the iterating and searching functions.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<h2 id="question-2">Question 2</h2>
<h3 id="test-suite">Test suite</h3>
<table>
<colgroup>
<col>
<col></colgroup>
<thead>
<tr class="header">
<th>Level</th>
<th>Criteria</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>0</td>
<td>
<ul>
<li>No submission for Q2 is made, or</li>
<li>The submitted code does not compile on&nbsp;<code>aviary.cs.umanitoba.ca</code>&nbsp;with the expected compilation commands.<code class="sourceCode bash"></code><code class="sourceCode bash"><span id="cb3-1"><span class="fu">make</span></span></code></li>
</ul>
</td>
</tr>
<tr class="even">
<td>1</td>
<td>
<ul>
<li>Code is submitted for the problem, and the code compiles.</li>
<li>The compiled code crashes, does not run, or does not complete in a reasonable amount of time (&lt; 5 seconds).</li>
<li>The C code is of high quality, following the standards described in the&nbsp;<a href="/d2l/le/content/518960/viewContent/3112728/View" target="_blank" rel="noopener">programming standards</a>&nbsp;document.</li>
</ul>
</td>
</tr>
<tr class="odd">
<td>2</td>
<td>
<ul>
<li>The criteria for 1 is met.</li>
<li>The testing suite produces a report at the end of execution clearly stating how many tests were executed, how many succeeded and how many failed.</li>
</ul>
</td>
</tr>
<tr class="even">
<td>3</td>
<td>
<ul>
<li>The criteria for 2 is met.</li>
<li>The creation and destruction functions for the set are tested.</li>
</ul>
</td>
</tr>
<tr class="odd">
<td>4</td>
<td>
<ul>
<li>The criteria for 3 is met.</li>
<li>The insertion and removal functions are tested.</li>
<li>Tests include both general case and edge case data.</li>
</ul>
</td>
</tr>
<tr class="even">
<td>5</td>
<td>
<ul>
<li>The criteria for 4 is met.</li>
<li>The set operation functions are tested.</li>
<li>Tests include both general case and edge case data.</li>
<li>Memory management (<code>validateMemUse</code>) is tested.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<h3 id="report">Report</h3>
A total of 5 points is available, one for each set implementation. Correctly reporting the buggy function(s)&nbsp;<strong>and</strong>&nbsp;what is buggy about the function for each set implementation is worth 1 point.

The report&nbsp;<strong>must</strong>&nbsp;be written as a&nbsp;<a href="https://guides.github.com/features/mastering-markdown/" target="_blank" rel="noopener">Markdown-formatted</a>&nbsp;file. You must&nbsp;<em>minimally</em>&nbsp;use headers to separate the report into sections, for example:

<div id="cb4" class="sourceCode">
<pre class="sourceCode markdown"><code class="sourceCode markdown"><span id="cb4-1">Set 1</span>
<span id="cb4-2"><span class="fu">=====</span></span>
<span id="cb4-3"></span>
<span id="cb4-4"><span class="ss">* </span>The function you think is buggy in set 1</span>
<span id="cb4-5"><span class="ss">* </span>What is buggy about that function?</span>
<span id="cb4-6"></span>
<span id="cb4-7">Set 2</span>
<span id="cb4-8"><span class="fu">=====</span></span>
<span id="cb4-9"></span>
<span id="cb4-10"><span class="ss">* </span>The function you think is buggy in set 2</span>
<span id="cb4-11"><span class="ss">* </span>What is buggy about that function?</span></code></pre>
</div>
