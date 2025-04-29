# algorithms-on-strings-assignment-2-burrows-wheeler-transform-and-suffix-arrays-solved
**TO GET THIS SOLUTION VISIT:** [Algorithms-on-Strings Assignment 2-Burrows–Wheeler Transform and Suffix Arrays Solved](https://www.ankitcodinghub.com/product/algorithms-on-strings-module-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115913&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Algorithms-on-Strings Assignment 2-Burrows–Wheeler Transform and Suffix Arrays Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Specialization: Data Structures and Algorithms

Programming Assignment 2:

Burrows–Wheeler Transform and Suffix Arrays

Introduction

Welcome to your second programming assignment of the Algorithms on Strings class! In this programming assignment, you will be practicing implementing Burrows–Wheeler transform and suffix arrays.

Recall that starting from this programming assignment, the grader will show you only the first few tests (see the questions 6.4 and 6.5 in the FAQ section).

Learning Outcomes

Upon completing this programming assignment you will be able to:

1. compute the Burrows–Wheeler transform (BWT) of a string;

2. compute the inverse of BWT;

3. use BWT for pattern matching;

4. construct the suffix array of a string.

Passing Criteria: 2 out of 4

Passing this programming assignment requires passing at least 2 out of 4 code problems from this assignment. In turn, passing a code problem requires implementing a solution that passes all the tests for this problem in the grader and does so under the time and memory limits specified in the problem statement.

Contents

1 Problem: Construct the Burrows–Wheeler Transform of a String 3

2 Problem: Reconstruct a String from its Burrows–Wheeler Transform 5

3 Problem: Implement BetterBWMatching 7

4 Problem: Construct the Suffix Array of a String 10

5 General Instructions and Recommendations on Solving Algorithmic Problems 13

5.1 Reading the Problem Statement . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

5.2 Designing an Algorithm . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

5.3 Implementing Your Algorithm . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

5.4 Compiling Your Program . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

5.5 Testing Your Program . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

5.6 Submitting Your Program to the Grading System . . . . . . . . . . . . . . . . . . . . . . . . . 15

5.7 Debugging and Stress Testing Your Program . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

6 Frequently Asked Questions 16

6.1 I submit the program, but nothing happens. Why? . . . . . . . . . . . . . . . . . . . . . . . . 16 6.2 I submit the solution only for one problem, but all the problems in the assignment are graded.

Why? . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16

6.3 What are the possible grading outcomes, and how to read them? . . . . . . . . . . . . . . . . 16

6.4 How to understand why my program fails and to fix it? . . . . . . . . . . . . . . . . . . . . . 17

6.5 Why do you hide the test on which my program fails? . . . . . . . . . . . . . . . . . . . . . . 17

6.7 My implementation always fails in the grader, though I already tested and stress tested it a

lot. Would not it be better if you give me a solution to this problem or at least the test cases

that you use? I will then be able to fix my code and will learn how to avoid making mistakes.

Otherwise, I do not feel that I learn anything from solving this problem. I am just stuck. . . 18

1 Problem: Construct the Burrows–Wheeler Transform of a String

Problem Introduction

Our goal is to further improve on the memory requirements of the suffix array.

Given a string Text, form all possible cyclic rotations of Text; a cyclic rotation is defined by chopping off a suffix from the end of Text and appending this suffix to the beginning of Text. Next — similarly to suffix arrays — order all the cyclic rotations of Text lexicographically to form a |Text| × |Text| matrix of symbols that we call the Burrows–Wheeler matrix and denote by M(Text).

Note that the first column of M(Text) contains the symbols of Text ordered lexicographically. In turn, the second column of M(Text) contains the second symbols of all cyclic rotations of Text, and so it too represents a (different) rearrangement of symbols from Text. The same reasoning applies to show that any column of M(Text) is some rearrangement of the symbols of Text. We are interested in the last column of M(Text), called the Burrows–Wheeler transform of Text, or BWT(Text).

Problem Description

Task. Construct the Burrows–Wheeler transform of a string.

Input Format. A string Text ending with a “$” symbol.

Constraints. 1 ≤ |Text| ≤ 1000; except for the last symbol, Text contains symbols A, C, G, T only.

Output Format. BWT(Text).

Time Limits.

language C C++ Java Python C# Haskell JavaScript Ruby Scala

time in seconds 0.5 0.5 0.75 0.5 0.75 1 2.5 2.5 1.5

Memory Limit. 512MB.

Sample 1.

Input:

AA$

Output:

AA$

Explanation:

M(Text) =

Sample 2.

Input:

ACACACAC$

Output:

CCCC$AAAA

Explanation:

A C $

$

$

M(Text) =

$

$

⎢⎣C A C A C $

C A C A C A C

Sample 3.

Input:

AGACATA$

Output:

ATG$CAAA

Explanation:

⎡$

A $

⎢ $

M(Text) =

$

⎢⎢C A T A $ A G A⎥⎥

⎢⎣G A C A T A $ A⎥⎦

T A $ A G A C A

Starter Files

The starter solutions for this problem read the input data from the standard input, pass it to a blank procedure, and then write the result to the standard output. You are supposed to implement your algorithm in this blank procedure if you are using C++, Java, or Python3. For other programming languages, you need to implement a solution from scratch. Filename: bwt

What To Do

To solve this problem, it is enough to construct BWT(Text) by sorting all cyclic rotations of BWT(Text).

Need Help?

Ask a question or see the questions asked by other learners at this forum thread.

2 Problem: Reconstruct a String from its Burrows–Wheeler Transform

Problem Introduction

In the previous problem, we introduced the Burrows–Wheeler transform of a string Text. In this problem, we give you the opportunity to reverse this transform.

Problem Description

Task. Reconstruct a string from its Burrows–Wheeler transform.

Input Format. A string Transform with a single “$” sign.

Constraints. 1 ≤ |Transform| ≤ 1000000; except for the last symbol, Text contains symbols A, C, G, T only.

Output Format. The string Text such that BWT(Text) = Transform. (There exists a unique such string.) Time Limits.

language C C++ Java Python C# Haskell JavaScript Ruby Scala

time in seconds 2 2 3 10 3 4 10 10 6

Memory Limit. 512MB.

Sample 1.

Input:

AC$A

Output:

ACA$

Explanation:

⎡$

M(Text) = ⎢⎢AA ⎣

C A

$

C

A C

A

A

$ A⎤

C⎥

$⎥⎦

A

Sample 2.

Input:

AGGGAA$

Output:

GAGAGA$

Explanation:

$

M(Text) = $

$

Starter Files

The starter solutions for this problem read the input data from the standard input, pass it to a blank procedure, and then write the result to the standard output. You are supposed to implement your algorithm in this blank procedure if you are using C++, Java, or Python3. For other programming languages, you need to implement a solution from scratch. Filename: bwtinverse

What To Do

To solve this problem, it is enough to implement carefully the corresponding algorithm covered in the lectures.

Need Help?

Ask a question or see the questions asked by other learners at this forum thread.

3 Problem: Implement BetterBWMatching

Problem Introduction

The algorithm BWMatching counts the total number of matches of Pattern in Text, where the only information that we are given is FirstColumn and LastColumn = BWT(Text) in addition to the Last-to-First mapping. The pointers top and bottom are updated by the green lines in the following pseudocode.

BWMatching(FirstColumn, LastColumn, Pattern, LastToFirst): top ← 0 bottom ← |LastColumn| − 1 while top ≤ bottom:

if Pattern isnonempty:

symbol ← lastletterin Pattern removelastletterfrom Pattern ifpositionsfrom top to bottom in LastColumn containanoccurrenceof symbol:

topIndex ← firstpositionof symbol amongpositionsfrom top to bottom in LastColumn bottomIndex ← lastpositionof symbol amongpositionsfrom top to bottom in LastColumn top ← LastToFirst(topIndex) bottom ← LastToFirst(bottomIndex)

else: return0

else:

return bottom − top + 1

The Last-to-First array, denoted LastToFirst(i), answers the following question: given a symbol at position i in LastColumn, what is its position in FirstColumn? For example, if Text = panamabananas$, BWT(Text) = smnpbnnaaaaa$a, FirstCol(Text) = $aaaaaabmnnnps, then we can rewrite

BWT(Text) = s1m1n1p1b1n2n3a1a2a3a4a5$1a6 and FirstCol(Text) = $1a1a2a3a4a5a6b1m1n1n2n3p1s1, and now we see that a3 in BWT(Text) corresponds to a3 in FirstCol(Text).

If you implement BWMatching, you probably will find the algorithm to be slow. The reason for its sluggishness is that updating the pointers top and bottom is time-intensive, since it requires examining every symbol in LastColumn between top and bottom at each step. To improve BWMatching, we introduce a function Countsymbol(i, LastColumn), which returns the number of occurrences of symbol in the first i positions of LastColumn. For example,

Count“n”(10,“smnpbnnaaaaa$a”) = 3 and Count“a”(4,“smnpbnnaaaaa$a”) = 0.

The green lines from BWMatching can be compactly described without the First-to-Last mapping by the following two lines:

top ← (Countsymbol + 1)-thoccurrenceofcharacter symbol in FirstColumn bottom ← positionof symbol withrank Countsymbol(bottom + 1, LastColumn)in FirstColumn

Define FirstOccurrence(symbol) as the first position of symbol in FirstColumn. If Text = “panamabananas$”, then FirstColumn is “$aaaaaabmnnnps”, and the array holding all values of FirstOccurrence is [0, 1, 7, 8, 9, 12, 13]. For DNA strings of any length, the array FirstOccurrence contains only five elements.

The two lines of pseudocode from the previous step can now be rewritten as follows:

top ← FirstOccurrence(symbol) + Countsymbol(top,LastColumn) bottom ← FirstOccurrence(symbol) + Countsymbol(bottom + 1,LastColumn) − 1 In the process of simplifying the green lines of pseudocode from BWMatching, we have also eliminated the need for both FirstColumn and LastToFirst, resulting in a more efficient algorithm called BetterBWMatching.

BWMatching(FirstOccurrence, LastColumn, Pattern, Count): top ← 0 bottom ← |LastColumn| − 1 while top ≤ bottom:

if Pattern isnonempty:

symbol ← lastletterin Pattern removelastletterfrom Pattern ifpositionsfrom top to bottom in LastColumn containanoccurrenceof symbol:

top ← FirstOccurrence(symbol) + Countsymbol(top,LastColumn)

bottom ← FirstOccurrence(symbol) + Countsymbol(bottom + 1,LastColumn) − 1

else: return0

else:

return bottom − top + 1

Problem Description

Task. Implement BetterBWMatching algorithm.

Input Format. A string BWT(Text), followed by an integer n and a collection of n strings Patterns = {p1,…,pn} (on one line separated by spaces).

Constraints. 1 ≤ |BWT(Text)| ≤ 106; except for the one $ symbol, BWT(Text) contains symbols A, C, G, T only; 1 ≤ n ≤ 5 000; for all 1 ≤ i ≤ n, pi is a string over A, C, G, T; 1 ≤ |pi| ≤ 1000.

Output Format. A list of integers, where the i-th integer corresponds to the number of substring matches of the i-th member of Patterns in Text.

Time Limits.

language C C++ Java Python C# Haskell JavaScript Ruby Scala

time in seconds 4 4 6 24 6 8 24 24 12

Memory Limit. 512MB.

Sample 1.

Input:

AGGGAA$

1

GA

Output:

3

Explanation:

In this case, Text = GAGAGA$. The pattern GA appears three times in it.

Sample 2.

Input:

ATT$AA

2

ATAA

Output:

23

Explanation:

Text = ATATA$ contains two occurrences of ATA and three occurrences of A.

Sample 3.

Input:

AT$TCTATG

2 TCTTATG

Output:

00

Explanation:

Text = ATCGTTTA does not contain any occurrences of two given patterns.

Starter Files

The starter solutions for this problem read the input data from the standard input, pass the Burrows– Wheeler Transform to a preprocessing procedure to precompute some useful values, then pass each pattern along with BWT and precomputed values to the procedure which counts the number of occurrences of the pattern in the text, and then write the result to the standard output. You are supposed to implement these two procedure which are left blank if you are using C++, Java, or Python3. For other programming languages, you need to implement a solution from scratch. Filename: bwmatching.

What To Do

To solve this problem, it is enough to carefully implement the algorithm described in the lectures. However, don’t forget that you need to do the preprocessing of the Text only once, and then use the results. If you do the preprocessing of the Text each time, there is no point in such preprocessing, you don’t save anything. But if you do the preprocessing once, save the results, and use them for searching each pattern, you save a lot on each search.

Need Help?

Ask a question or see the questions asked by other learners at this forum thread.

4 Problem: Construct the Suffix Array of a String

Problem Introduction

We saw that suffix trees can be too memory intensive to apply in practice.

In 1993, Udi Manber and Gene Myers introduced suffix arrays as a memory-efficient alternative to suffix trees. To construct SuffixArray(Text), we first sort all suffixes of Text lexicographically, assuming that “$” comes first in the alphabet. The suffix array is the list of starting positions of these sorted suffixes. For example,

SuffixArray(“panamabananas$”) = (13,5,3,1,7,9,11,6,4,2,8,10,0,12)

Problem Description

Task. Construct the suffix array of a string.

Input Format. A string Text ending with a “$” symbol.

Constraints. 1 ≤ |Text(Text)| ≤ 104; except for the last symbol, Text contains symbols A, C, G, T only.

Output Format. SuffixArray(Text), that is, the list of starting positions (0-based) of sorted suffixes separated by spaces.

Time Limits.

language C C++ Java Python C# Haskell JavaScript Ruby Scala

time in seconds 1 1 2 1 1.5 2 5 5 4

Memory Limit. 512MB.

Sample 1.

Input:

GAC$

Output:

3120

Explanation:

Sorted suffixes:

3 $

1 AC$ 2 C$ 0 GAC$

Sample 2.

Input:

GAGAGAGA$

Output:

875316420

Explanation:

Sorted suffixes:

8 $

7 A$ 5 AGA$ 3 AGAGA$ 1 AGAGAGA$ 6 GA$ 4 GAGA$ 2 GAGAGA$ 0 GAGAGAGA$

Sample 3.

Input:

AACGATAGCGGTAGA$

Output:

1514011264281337910115

Explanation:

Sorted suffixes:

15 $

14 A$

0 AACGATAGCGGTAGA$ 1 ACGATAGCGGTAGA$ 12 AGA$ 6 AGCGGTAGA$ 4 ATAGCGGTAGA$ 2 CGATAGCGGTAGA$ 8 CGGTAGA$ 13 GA$ 3 GATAGCGGTAGA$ 7 GCGGTAGA$ 9 GGTAGA$ 10 GTAGA$ 11 TAGA$ 5 TAGCGGTAGA$

Starter Files

The starter solutions for this problem read the input data from the standard input, pass it to a blank procedure, and then write the result to the standard output. You are supposed to implement your algorithm in this blank procedure if you are using C++, Java, or Python3. For other programming languages, you need to implement a solution from scratch. Filename: suffix_array

What To Do

To solve this problem, it is enough to just sort all suffixes of Text.

Need Help?

Ask a question or see the questions asked by other learners at this forum thread.

5 General Instructions and Recommendations on Solving Algorithmic Problems

Your main goal in an algorithmic problem is to implement a program that solves a given computational problem in just few seconds even on massive datasets. Your program should read a dataset from the standard input and write an answer to the standard output.

Below we provide general instructions and recommendations on solving such problems. Before reading them, go through readings and screencasts in the first module that show a step by step process of solving two algorithmic problems: link.

5.1 Reading the Problem Statement

You start by reading the problem statement that contains the description of a particular computational task as well as time and memory limits your solution should fit in, and one or two sample tests. In some problems your goal is just to implement carefully an algorithm covered in the lectures, while in some other problems you first need to come up with an algorithm yourself.

5.2 Designing an Algorithm

If your goal is to design an algorithm yourself, one of the things it is important to realize is the expected running time of your algorithm. Usually, you can guess it from the problem statement (specifically, from the subsection called constraints) as follows. Modern computers perform roughly 108–109 operations per second. So, if the maximum size of a dataset in the problem description is n = 105, then most probably an algorithm with quadratic running time is not going to fit into time limit (since for n = 105, n2 = 1010) while a solution with running time O(nlogn) will fit. However, an O(n2) solution will fit if n is up to 103 = 1000, and if n is at most 100, even O(n3) solutions will fit. In some cases, the problem is so hard that we do not know a polynomial solution. But for n up to 18, a solution with O(2nn2) running time will probably fit into the time limit.

To design an algorithm with the expected running time, you will of course need to use the ideas covered in the lectures. Also, make sure to carefully go through sample tests in the problem description.

5.3 Implementing Your Algorithm

When you have an algorithm in mind, you start implementing it. Currently, you can use the following programming languages to implement a solution to a problem: C, C++, C#, Haskell, Java, JavaScript, Python2, Python3, Ruby, Scala. For all problems, we will be providing starter solutions for C++, Java, and Python3. If you are going to use one of these programming languages, use these starter files. For other programming languages, you need to implement a solution from scratch.

5.4 Compiling Your Program

For solving programming assignments, you can use any of the following programming languages: C, C++, C#, Haskell, Java, JavaScript, Python2, Python3, Ruby, and Scala. However, we will only be providing starter solution files for C++, Java, and Python3. The programming language of your submission is detected automatically, based on the extension of your submission.

We have reference solutions in C++, Java and Python3 which solve the problem correctly under the given restrictions, and in most cases spend at most 1/3 of the time limit and at most 1/2 of the memory limit. You can also use other languages, and we’ve estimated the time limit multipliers for them, however, we have no guarantee that a correct solution for a particular problem running under the given time and memory constraints exists in any of those other languages.

∙ C (gcc 5.2.1). File extensions: .c. Flags:

gcc -pipe -O2 -std=c11 &lt;filename&gt; -lm

∙ C++ (g++ 5.2.1). File extensions: .cc, .cpp. Flags:

g++ -pipe -O2 -std=c++14 &lt;filename&gt; -lm

∙ C# (mono 3.2.8). File extensions: .cs. Flags:

mcs

∙ Haskell (ghc 7.8.4). File extensions: .hs. Flags:

ghc -O

∙ Java (Open JDK 8). File extensions: .java. Flags:

javac -encoding UTF-8 java -Xmx1024m

∙ JavaScript (Node v6.3.0). File extensions: .js. Flags:

nodejs

∙ Python 2 (CPython 2.7). File extensions: .py2 or .py (a file ending in .py needs to have a first line which is a comment containing “python2”). No flags:

python2

∙ Python 3 (CPython 3.4). File extensions: .py3 or .py (a file ending in .py needs to have a first line which is a comment containing “python3”). No flags:

python3

∙ Ruby (Ruby 2.1.5). File extensions: .rb.

ruby

∙ Scala (Scala 2.11.6). File extensions: .scala.

scalac

5.5 Testing Your Program

When your program is ready, you start testing it. It makes sense to start with small datasets — for example, sample tests provided in the problem description. Ensure that your program produces a correct result.

You then proceed to checking how long does it take your program to process a massive dataset. For this, it makes sense to implement your algorithm as a function like solve(dataset) and then implement an additional procedure generate() that produces a large dataset. For example, if an input to a problem is a sequence of integers of length 1 ≤ n ≤ 105, then generate a sequence of length exactly 105, pass it to your solve() function, and ensure that the program outputs the result quickly.

Also, check the boundary values. Ensure that your program processes correctly sequences of size n = 1,2,105. If a sequence of integers from 0 to, say, 106 is given as an input, check how your program behaves when it is given a sequence 0,0,…,0 or a sequence 106,106,…,106. Check also on randomly generated data. For each such test check that you program produces a correct result (or at least a reasonably looking result).

In the end, we encourage you to stress test your program to make sure it passes in the system at the first attempt. See the readings and screencasts from the first week to learn about testing and stress testing: link.

5.6 Submitting Your Program to the Grading System

When you are done with testing, you submit your program to the grading system. For this, you go the submission page, create a new submission, and upload a file with your program. The grading system then compiles your program (detecting the programming language based on your file extension, see Subsection 5.4) and runs it on a set of carefully constructed tests to check that your program always outputs a correct result and that it always fits into the given time and memory limits. The grading usually takes no more than a minute, but in rare cases when the servers are overloaded it might take longer. Please be patient. You can safely leave the page when your solution is uploaded.

5.7 Debugging and Stress Testing Your Program

If your program failed, you will need to debug it. Most probably, you didn’t follow some of our suggestions from the section 5.5. See the readings and screencasts from the first week to learn about debugging your program: link.

You are almost guaranteed to find a bug in your program using stress testing, because the way these programming assignments and tests for them are prepared follows the same process: small manual tests, tests for edge cases, tests for large numbers and integer overflow, big tests for time limit and memory limit checking, random test generation. Also, implementation of wrong solutions which we expect to see and stress testing against them to add tests specifically against those wrong solutions.

Go ahead, and we hope you pass the assignment soon!

6 Frequently Asked Questions

6.1 I submit the program, but nothing happens. Why?

You need to create submission and upload the file with your solution in one of the programming languages C, C++, Java, or Python (see Subsections 5.3 and 5.4). Make sure that after uploading the file with your solution you press on the blue “Submit” button in the bottom. After that, the grading starts, and the submission being graded is enclosed in an orange rectangle. After the testing is finished, the rectangle disappears, and the results of the testing of all problems is shown to you.

6.2 I submit the solution only for one problem, but all the problems in the assignment are graded. Why?

Each time you submit any solution, the last uploaded solution for each problem is tested. Don’t worry: this doesn’t affect your score even if the submissions for the other problems are wrong. As soon as you pass the sufficient number of problems in the assignment (see in the pdf with instructions), you pass the assignment. After that, you can improve your result if you successfully pass more problems from the assignment. We recommend working on one problem at a time, checking whether your solution for any given problem passes in the system as soon as you are confident in it. However, it is better to test it first, please refer to the reading about stress testing: link.

6.3 What are the possible grading outcomes, and how to read them?

Good job! Hurrah! Your solution passed, and you get a point!

Wrong answer. Your solution has output incorrect answer for some test case. If it is a sample test case from the problem statement, or if you are solving Programming Assignment 1, you will also see the input data, the output of your program and the correct answer. Otherwise, you won’t know the input, the output, and the correct answer. Check that you consider all the cases correctly, avoid integer overflow, output the required white space, output the floating point numbers with the required precision, don’t output anything in addition to what you are asked to output in the output specification of the problem statement. See this reading on testing: link.

Time limit exceeded. Your solution worked longer than the allowed time limit for some test case. If it is a sample test case from the problem statement, or if you are solving Programming Assignment 1, you will also see the input data and the correct answer. Otherwise, you won’t know the input and the correct answer. Check again that your algorithm has good enough running time estimate. Test your program locally on the test of maximum size allowed by the problem statement and see how long it works. Check that your program doesn’t wait for some input from the user which makes it to wait forever. See this reading on testing: link.

Memory limit exceeded. Your solution used more than the allowed memory limit for some test case. If it is a sample test case from the problem statement, or if you are solving Programming Assignment 1,

you will also see the input data and the correct answer. Otherwise, you won’t know the input and the correct answer. Estimate the amount of memory that your program is going to use in the worst case and check that it is less than the memory limit. Check that you don’t create too large arrays or data structures. Check that you don’t create large arrays or lists or vectors consisting of empty arrays or empty strings, since those in some cases still eat up memory. Test your program locally on the test of maximum size allowed by the problem statement and look at its memory consumption in the system.

Cannot check answer. Perhaps output format is wrong. This happens when you output something completely different than expected. For example, you are required to output word “Yes” or “No”, but you output number 1 or 0, or vice versa. Or your program has empty output. Or your program outputs not only the correct answer, but also some additional information (this is not allowed, so please follow exactly the output format specified in the problem statement). Maybe your program doesn’t output anything, because it crashes.

Unknown signal 6 (or 7, or 8, or 11, or some other). This happens when your program crashes. It can be because of division by zero, accessing memory outside of the array bounds, using uninitialized variables, too deep recursion that triggers stack overflow, sorting with contradictory comparator, removing elements from an empty data structure, trying to allocate too much memory, and many other reasons. Look at your code and think about all those possibilities. Make sure that you use the same compilers and the same compiler options as we do. Try different testing techniques from this reading: link.

Internal error: exception… Most probably, you submitted a compiled program instead of a source code.

Grading failed. Something very wrong happened with the system. Contact Coursera for help or write in the forums to let us know.

6.4 How to understand why my program fails and to fix it?

If your program works incorrectly, it gets a feedback from the grader. For the Programming Assignment 1, when your solution fails, you will see the input data, the correct answer and the output of your program in case it didn’t crash, finished under the time limit and memory limit constraints. If the program crashed, worked too long or used too much memory, the system stops it, so you won’t see the output of your program or will see just part of the whole output. We show you all this information so that you get used to the algorithmic problems in general and get some experience debugging your programs while knowing exactly on which tests they fail.

However, in the following Programming Assignments throughout the Specialization you will only get so much information for the test cases from the problem statement. For the next tests you will only get the result: passed, time limit exceeded, memory limit exceeded, wrong answer, wrong output format or some form of crash. We hide the test cases, because it is crucial for you to learn to test and fix your program even without knowing exactly the test on which it fails. In the real life, often there will be no or only partial information about the failure of your program or service. You will need to find the failing test case yourself. Stress testing is one powerful technique that allows you to do that. You should apply it after using the other testing techniques covered in this reading.

6.5 Why do you hide the test on which my program fails?

Often beginner programmers think by default that their programs work. Experienced programmers know, however, that their programs almost never work initially. Everyone who wants to become a better programmer needs to go through this realization.

When you are sure that your program works by default, you just throw a few random test cases against it, and if the answers look reasonable, you consider your work done. However, mostly this is not enough. To make one’s programs work, one must test them really well. Sometimes, the programs still don’t work although you tried really hard to test them, and you need to be both skilled and creative to fix your bugs. Solutions to algorithmic problems are one of the hardest to implement correctly. That’s why in this Specialization you will gain this important experience which will be invaluable in the future when you write programs which you really need to get right.

It is crucial for you to learn to test and fix your programs yourself. In the real life, often there will be no or only partial information about the failure of your program or service. Still, you will have to reproduce the failure to fix it (or just guess what it is, but that’s rare, and you will still need to reproduce the failure to make sure you have really fixed it). When you solve algorithmic problems, it is very frequent to make subtle mistakes. That’s why you should apply the testing techniques described in this reading to find the failing test case and fix your program.

(link).

6.7 My implementation always fails in the grader, though I already tested and stress tested it a lot. Would not it be better if you give me a solution to this problem or at least the test cases that you use? I will then be able to fix my code and will learn how to avoid making mistakes. Otherwise, I do not feel that I learn anything from solving this problem. I am just stuck.

First of all, you always learn from your mistakes.

The process of trying to invent new test cases that might fail your program and proving them wrong is often enlightening. This thinking about the invariants which you expect your loops, ifs, etc. to keep and proving them wrong (or right) makes you understand what happens inside your program and in the general algorithm you’re studying much more.

Also, it is important to be able to find a bug in your implementation without knowing a test case and without having a reference solution. Assume that you designed an application and an annoyed user reports that it crashed. Most probably, the user will not tell you the exact sequence of operations that led to a crash. Moreover, there will be no reference application. Hence, once again, it is important to be able to locate a bug in your implementation yourself, without a magic oracle giving you either a test case that your program fails or a reference solution. We encourage you to use programming assignments in this class as a way of practicing this important skill.
