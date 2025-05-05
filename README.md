# cse330---operating-systems-project-2-solved
**TO GET THIS SOLUTION VISIT:** [CSE330 – Operating Systems Project #2 Solved](https://www.ankitcodinghub.com/product/cse330-operating-systems-project-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;56805&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE330 - Operating Systems Project #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Part 1: <strong>(This part of the project is not graded.)</strong>

<strong>Overview</strong>:

For this project you are to write routines that perform standard queuing functions. The functions work on multiple queues, and structure each queue as a doubly linked, circular list.

<strong>Data Structures:</strong>

A queue consists of a head-pointer and a set of q-elements.

A q-element is a structure, consisting of a prev and next pointer, and a payload consisting of 1 integer. The header is a pointer to the first element of the queue<em>. The</em> <em>head pointer is “null” if the q is empty.</em>

<strong>Functions</strong>:

The functions that you implement are:

<ol>
<li><strong>item = NewItem</strong>(); // returns a pointer to a new q-element</li>
<li><strong>InitQueue</strong>( &amp;head) // creates a empty queue, pointed to by the variable head.</li>
</ol>
&nbsp;

<ol start="3">
<li><strong>AddQueue</strong>(&amp;head, item) // adds a queue item, pointed to by “item”, to the queue pointed to by head.</li>
</ol>
&nbsp;

<ol start="4">
<li>item = <strong>DelQueue</strong>(&amp;head) // deletes an item from head and returns a pointer to the deleted item</li>
</ol>
&nbsp;

<ol start="5">
<li><strong>RotateQ</strong>(&amp;head) // Moves the header pointer to the next element in the queue. This is equivalent to AddQ(&amp;head, DeleteQ(&amp;head)), but is simpler to use and more efficient to implement.</li>
</ol>
&nbsp;

&nbsp;

<strong>Note</strong>: All the routines work on pointers. They do<strong> <em>not</em> </strong>copy q-elements. Also they to not allocate/deallocate space (except NewItem()). You may choose to implement a <strong>FreeItem</strong>(item) function – optional.

&nbsp;

<strong>Implementation and Testing</strong>

&nbsp;

The routines should be implemented in C under the Linux operating system. If you are not familiar with Linux and/or do not have it installed. Please use a Ubuntu Virtual Machine. For more details/questions post requests on the discussion board.

&nbsp;

All the above routines and data structures are to be placed in 1 file, called “q.h”. Do not include other files into this file. The test routines can be in “proj-1.c” and this will include q.h and other standard header files.

&nbsp;

Write test routines that thoroughly test the queue implementation. Use multiple queues. Pay special attention to deleting the last element of a q. Also make sure “RotateQ” is behaves properly (strange behavior of this routine means the insert/delete routines have bugs.)

&nbsp;

Further warning: Bugs in the Q routines have been the #1 cause for strange errors in the project, always. Careful that you get it right, else things will go bump later.

&nbsp;

&nbsp;

Part 2: <strong>(This part of the project is graded.)</strong>

&nbsp;

&nbsp;

<strong>Overview</strong>:

&nbsp;

Using the queuing routines (not all will be used) this project will implement the ability to run multiple functions as threads, using non-preemptive scheduling.

&nbsp;

<strong>Step 1: TCB and context</strong>:

&nbsp;

The queue items defined in your q.h file has to changed, to be of type TCB_t. The TCB_t and an initialization routine are provided in a header file <a href="../Documents/CSE430Notes/430-assignments/tcb.h">tcb.h</a>. Note that TCB_t has previous and next pointers along with an ucontext_t field to store a thread context.

&nbsp;

There is a routine in the tcb.h file called init_TCB, which is used to initialize a TCB for a new thread. The arguments to init_TCB are:

&nbsp;

<ol>
<li>pointer to the function, to be executed</li>
<li>pointer to the thread stack</li>
<li>size of the stack</li>
</ol>
&nbsp;

&nbsp;

Step 1 consists of understanding tcb.h and changing the q-element type in your q.h file to TCB_t

&nbsp;

&nbsp;

<strong>Step 2:</strong>

&nbsp;

Write a routine called start_thread and put it in a file called “<strong>threads.h”.</strong> Also routines defined in Step 3 will go into this file. You will need to include q.h into threads.h. The code for start_thread looks like:

&nbsp;

<strong>void start_thread(void (*function)(void))</strong>

{ // begin pseudo code

allocate a stack (via malloc) of a certain size (choose 8192)

&nbsp;

allocate a TCB (via malloc)

call init_TCB with appropriate arguments

&nbsp;

call addQ to add this TCB into the “RunQ” which is a global header pointer

//end pseudo code

&nbsp;

}

&nbsp;

<strong>Step 3:</strong>

&nbsp;

Write the routines called “yield” and “run” which cranks up the works (and put them in threads.h). These routines are defined as:

&nbsp;

<strong>void run()</strong>

{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // real code

&nbsp;

ucontext_t parent;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // get a place to store the main context, for

faking

getcontext(&amp;parent);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // magic sauce

swapcontext(&amp;parent, &amp;(RunQ-&gt;conext));&nbsp;&nbsp;&nbsp;&nbsp; // start the first thread

}

&nbsp;

<strong>void yield() // similar to run</strong>

&nbsp;

{

rotate the run Q;

swap the context, from previous thread to the thread pointed to by RunQ

&nbsp;

}

&nbsp;

<strong>Step 4:</strong>

&nbsp;

Write a driver program in a file called thread_test.c. Into thread_test.c.c include threads.h which includes q.h, which includes TCB.h, which includes ucontext.h.

&nbsp;

Declare a global RunQ.

&nbsp;

Write N functions with while loops (put a yield in each loop) counting the number of times each function is executed. There should be one global variable. Each function will have a local variable. Each function should increment the local variable by 1 and the global variable by the thread ID. If there were three functions in three threads (one in each thread), the first function will increment the global variable by 1 and the local variable by 1, the second function should increment the global variable by 2 and local variable by 1, the third function will increment the global variable by 3 and the local variable by 1. Each function should print the following before yielding

&nbsp;

<em>printf(“This is %d th execution of thread X with global var value % d”, local variable, global variable)</em>

&nbsp;

<em>Where X can be 1 2 and 3 depending on the thread ID</em>

<em>&nbsp;</em>

<strong>Test cases</strong>

&nbsp;

Each test case will have two numbers of the form

A,B

&nbsp;

Here A is the total number of threads and B is the number of times each thread should be executed.

&nbsp;

For example if a test case input is

&nbsp;

2,3

&nbsp;

You should output the following

&nbsp;

&nbsp;

This is 1 th execution of thread 1 with global var value 1

&nbsp;

This is 1 th execution of thread 2 with global var value 3

&nbsp;

This is 2 th execution of thread 1 with global var value 4

&nbsp;

This is 2 th execution of thread 2 with global var value 6

&nbsp;

This is 3 th execution of thread 1 with global var value 7

&nbsp;

This is 3 th execution of thread 2 with global var value 9

&nbsp;

&nbsp;

To get the output simply use the following code in command line

&nbsp;

gcc thread_test.c -o a.out

./a.out &lt; test_case_file.txt &gt; output_file.txt

&nbsp;

If A = 0 then output

No Threads

<strong>__________________________________</strong>

&nbsp;

<strong>tcb.h</strong>

&nbsp;

#include &lt;ucontext.h&gt;

&nbsp;

typedef struct TCB_t {

<table>
<tbody>
<tr>
<td width="152">struct TCB_t</td>
<td width="80">*next;</td>
</tr>
<tr>
<td width="152">struct TCB_t</td>
<td width="80">*prev;</td>
</tr>
<tr>
<td width="152">ucontext_t</td>
<td width="80">context;</td>
</tr>
<tr>
<td width="152">} TCB_t;</td>
<td width="80"></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

&nbsp;

void init_TCB (TCB_t *tcb, void *function, void *stackP, int stack_size) {

&nbsp;

&nbsp;

memset(tcb, ‘\0’, sizeof(TCB_t)); getcontext(&amp;tcb-&gt;context);

// wash, rinse

&nbsp;

// have to get parent context,

&nbsp;

&nbsp;

else snow forms on hell tcb-&gt;context.uc_stack.ss_sp = stackP;

&nbsp;

tcb-&gt;context.uc_stack.ss_size = (size_t) stack_size; makecontext(&amp;tcb-&gt;context, function, 0);// context is now cooked

}

&nbsp;

<strong>SUBMIT:</strong>

Your project must consist of 4 files

&nbsp;

<ol>
<li>h (uses ucontext.h) // this can be a copy of the file provided</li>
<li>h (includes TCB.h)</li>
<li>h (includes q.h)</li>
</ol>
&nbsp;

<ol start="4">
<li>c (includes threads.h) – must contain your name(s) in comments @ beginning</li>
</ol>
&nbsp;

(make sure the compile command, “gcc thread_test.c” does the correct

&nbsp;

compilation).

&nbsp;

All 4 files are to be ZIPPED into one zip or gzip file. The name of this file should reflect the name of the student (abbreviated, do not make it too long).

&nbsp;

Submit in Canvas.

&nbsp;

<strong>Note: Grading is on Ubuntu. It is in your interest to make sure the program compiles and runs in the target test platform.</strong>

<strong>&nbsp;</strong>

<strong>Testing your code on grading test cases</strong>

Grading test cases are different from the test cases provided.

To test your code against grading testcases follow these steps:

&nbsp;

Put the four files q.h tcb.h threads.h and thread_test.c in one zip folder with name YOUR LAST NAMEProject1.zip

&nbsp;

For example BanerjeeProject1.zip. <strong>Do not put the files in a folder and zip. The test server expects that after uncompressing it only sees the files and not a folder inside.</strong>

&nbsp;

The submission site is: <a href="http://10.218.107.121/index3.html">http://10.218.107.121/index3.html</a>

&nbsp;

In order to access the submission site you need to first login to sslvpn.asu.edu using you ASU ID and password. You will be asked to download cisco vpn. Please do so. For any subsequent time you want to access the submission site you have to login to sslvpn.asu.edu.

In the site there will be an option to upload one file. Please upload YOURLASTNAMEProject1.zip file there. Then please hit upload. Wait for 5 seconds and then you can see the evaluation of your code on the grading test cases. To access the evaluation please type in

&nbsp;

<a href="http://10.218.107.121/YOURLASTNAMEProject1.output">http://10.218.107.121/YOURLASTNAMEProject1.output</a>

&nbsp;

such as

&nbsp;

<a href="http://10.218.107.121/%20BanerjeeProject1.output">http://10.218.107.121/ BanerjeeProject1.output</a>

&nbsp;

Then download the text file and open with any text editor. If your code passed one test case then the corresponding test case will show “NO ERRORS HERE”

If it failed a given test case then it will print “——————————”

&nbsp;

At the end of the file the total number of test cases you passed will be displayed.

&nbsp;
