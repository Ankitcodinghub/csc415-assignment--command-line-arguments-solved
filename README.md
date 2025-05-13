# csc415-assignment--command-line-arguments-solved
**TO GET THIS SOLUTION VISIT:** [CSC415 Assignment -Command Line Arguments Solved](https://www.ankitcodinghub.com/product/csc415-assignment-command-line-arguments-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93548&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC415 Assignment -Command Line Arguments Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

This program is to demonstrate the usage of command line arguments in a C program. You will write this to run in the Linux virtual machine. The program should display the number of arguments from the command line and list each one on the console.

Here is a sample execution:

“`

student:~/CSC415$ make run RUNOPTIONS=”Hello, these are overridden options 3 6 9″

gcc -c -o bierman_robert_hw1_main.o bierman_robert_hw1_main.c -g -I.

gcc -o bierman_robert_hw1_main bierman_robert_hw1_main.o -g -I.

./bierman_robert_hw1_main Hello, these are overridden options 3 6 9

There were 9 arguments on the command line.

Argument 00: ./bierman_robert_hw1_main

Argument 01: Hello,

Argument 02: these

Argument 03: are

Argument 04: overridden

Argument 05: options

Argument 06: 3

Argument 07: 6

Argument 08: 9

student:~/CSC415$

“`

You should submit your source code file(s), Makefile along with a short writeup in PDF format into your GIT repository and submit the PDF into the assignment in iLearn. Your write-up should include a description of the project and what you did, issues you had, how you overcame the issues and the compilation and execution output from your program (screen shots embedded in the PDF document. Your execution output should include commands with the command-line arguments.

All filenames should be `&lt;lastname&gt;_&lt;firstname&gt;_HW&lt;#&gt;_&lt;component&gt;.&lt;proper extension&gt;`

So my filename would be `Bierman_Robert_HW1_main.c`

“`

# File: Makefile

LASTNAME=Bierman

FIRSTNAME=Robert

HW=1

RUNOPTIONS=Hello World

ROOTNAME=$(LASTNAME)_$(FIRSTNAME)_HW

FOPTION=_main

CC=gcc

CFLAGS= -g -I.

# To add libraries, add “-l &lt;libname&gt;”, for multiple repeat prior for each lib.

LIBS =

DEPS =

OBJ = $(ROOTNAME)$(HW)$(FOPTION).o

%.o: %.c $(DEPS)

$(CC) -c -o $@ $&lt; $(CFLAGS)

$(ROOTNAME)$(HW)$(FOPTION): $(OBJ)

$(CC) -o $@ $^ $(CFLAGS) $(LIBS)

clean:

rm *.o $(ROOTNAME)$(HW)$(FOPTION)

run: $(ROOTNAME)$(HW)$(FOPTION)

./$(ROOTNAME)$(HW)$(FOPTION) $(RUNOPTIONS)

“`

&nbsp;
