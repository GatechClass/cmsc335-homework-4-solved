# cmsc335-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CMSC335 Homework 4 Solved](https://mantutor.com/product/cmsc335-homework-4-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113700&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC335  Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
1. (20 pts) For the following program, explain the interesting elements related to threads. Focus on explaining the output of the program.

1 public class TaskThreadDemo {

2 public static void main (String args []) {

3 String [] sa = {“a”, “X”, “+”, “.”};

4 for (String s: sa) {

5 Runnable ps = new PrintChar (s, 200);

6 Thread ts = new Thread (ps, s);

7 ts.start ();

8 } // end for each character

9 } // end main

10 } // end class TaskThreadDemo

11

12 class PrintChar implements Runnable {

13 String ch;

14 int times;

15

16 public PrintChar (String c, int n) {

17 ch = c;

18 times = n;

19 } // end constructor

20

21 public void run () {

22 for (int i = 0; i &lt; times; i++) {

23 System.out.print (ch);

24 } // end for loop

25 } // end method run

26 } // end class PrintChar

2. (20 pts) What is changed if the method called on line 7, start(), is replaced with run()? Explain (of course). Focus on explaining the output of the program.

3. (20 pts) What is changed if the method Thread.yield() is added between lines 23 and 24? Explain. Focus on explaining the output of the program.

4. (20 pts) Modify the above program so that the Thread.sleep method is called after each character has been printed causing it to sleep for 500 milliseconds. Describe how that modification has altered the output and explain why the change had the effect that you described.

5. (20 pts) Modify the above program so that the Thread.sleep method is called after each thread is created in the main method causing it to sleep for 500 milliseconds. Describe how that modification has altered the output and explain why the change had the effect that you described.

1

Grading Rubric:

Attribute Meets Does not meet

Problem 1 20 points

Explains the interesting elements related to threads. Focuses on explaining the output of the program. 0 points

Does not explain the interesting elements related to threads. Does not focus on explaining the output of the program.

Problem 2 20 points

Explains what is changed if the method called on line 7, start(), is replaced with run().Focuses on explaining the output of the program. 0 points

Does not explain what is changed if the method called on line 7, start(), is replaced with run(). Does not focus on explaining the output of the program.

Problem 3 20 points

Explains what is changed if the method Thread.yield() is added between lines 23 and 24. Focuses on explaining the output of the program. 0 points

Does not explain what is changed if the method Thread.yield() is added between lines 23 and 24. Does not focus on explaining the output of the program.

Problem 4 20 points

Explains how the output is changed if the Thread.sleep method is called after each character has been printed. 0 points

Does not explain how the output is changed if the Thread.sleep method is called after each character has been printed.

Problem 5 20 points

Explains how the output is changed if the Thread.sleep method is called after each thread is created in the main method. 0 points

Does not explain how the output is changed if the Thread.sleep method is called after each thread is created in the main method.

2
