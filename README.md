# cis3360---security-in-computing-hw-2-checksum-solved
**TO GET THIS SOLUTION VISIT:** [CIS3360 – Security in Computing HW #2 Checksum Solved](https://www.ankitcodinghub.com/product/cis3360-security-in-computing-spring-2020-hw-2-checksum-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;53276&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS3360 – Security in Computing  HW #2 Checksum Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this assignment you’ll write a program that calculates the checksum for the text in a file. Your&nbsp; program will take two command line parameters. The first parameter will be the name of the input&nbsp; file for calculating the checksum. The second parameter will be for the size of the checksum (8, 16,&nbsp; or 32 bits). The program must generate output to the console (terminal) screen as specified below.

Command Line Parameters

1. Your program must compile and run from the command line.

2. The program executable must be named “checksum” (all lower case, no spaces or file&nbsp; extension).

3. Input the required file names as command line parameters. Your program may NOT&nbsp; prompt the user to enter the file names. The first parameter must be the name of the&nbsp; file used for calculating the checksum, as described below. The second parameter must&nbsp; be the size, in bits, of the checksum. The sample run command near the end of this&nbsp; document contains an example of how the parameters will be entered.

4. Your program should open the two files, echo the processed input to the screen, make&nbsp; the necessary calculations, and then output the ciphertext to the console (terminal)&nbsp; screen in the format described below.

Program Submission Instructions:

• You must submit your source code file

• The source code file must be submitted in Webcourses from the assignment page

• All source code must be in exactly one file of type .c, .cpp, or .java

Checksum size

The checksum size is a single integer, passed as the first command line argument. The valid values&nbsp; are the size of the checksum, which can be 8, 16, or 32 bits. Therefore, if the first parameter is not one of the valid values, the program should advise the user that the value is incorrect with a&nbsp; message formatted as shown below:

printf(“Valid checksum sizes are 8, 16, or 32\n”);

The message should be sent to STDERR.

Format of the input file

The input file will consist of the valid ASCII characters associated with the average text file. This&nbsp; includes punctuation, numbers, special characters, and whitespace.

Output Format

The program must output the following to the console (terminal) screen:

1. Echo the input file

2. Print the checksum.

The echoed input text should be in rows of exactly 80 characters per row (not counting the

NEWLINE character), except for the last row, which may possibly have fewer. These characters

should correspond to the input text. The checksum line should be formatted as follows:

X bit checksum is Y for all ZZZ chars

Using the following:

printf(“%2d bit checksum is %8lx for all %4d chars\n”,

checkSumSize, checksum, characterCount);

Where X is the checksum size (checkSumSize) of 8, 16, or 32, Y is the calculated checksum (checksum), and ZZZ is the character count (characterCount) of the input file. Note that the&nbsp; checksums are masked to print the appropriate sizes such two hex characters for 8 bits, 4 hex

characters for the 16 bit checksum, and 8 hex characters for 32 bit checksum. (Note that the format&nbsp; specifier for the checksum is %8lx, or the percent sign, the number 8, the letter l, and the letter x.)

What to submit to WebCourses

You must submit this assignment’s source code, appropriately commented, via WebCourses.

Program Notes and Hints

Your program must read in an input text file that may contain uppercase letters, lowercase letters

and non-letter characters. Your program should then calculate the checksum appropriately for the

size specified in the command line. Specifically, if the checksum is 8 bits long, each character should

be used as the number to be added to the checksum. Likewise, if the checksum is 16 bits long, each

two characters should be added to the checksum. Note that there is a 50% chance that there will be

one character short on the input file. In that case use the character “X” (an uppercase X) as the pad

character. Similarly, if the checksum is 32 bits, use the same technique and character to pad the

input string appropriately with 1, 2, or 3 pad characters (X). Correspondingly, some adjustment to

the file termination character NEWLINE may be required to match the expected output files.

Sample Run Command

C or C++ program:

Prompt$ ./checksum inputText1.txt 8

Java program:

Prompt$ java checksum inputText1.txt 8
