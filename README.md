# csci231-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [CSCI231 Lab 5 Solved](https://www.ankitcodinghub.com/product/csci231-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97000&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI231 Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

1. ​As a simple variation of the homework problem 8​, implement a procedure string_bubble_sort in MIPS assembly language that, given a string ​S and its ​length​, sort ​S​. You should print out the original string and the sorted string respectively.

For example, if ​S =“HelloWorld” and ​length = 10, then after calling your procedure ​S becomes “HWdellloor”, and this reversed ​S should be printed out. (NOTE: ​S = “H ello” and ​length = 6, ​S becomes “ Hello”, assuming each space will be calculated as an each length with the corresponding ASCII code).

In the program, we assume the variables (e.g., ​S ​and​ length​) should be declared and initialized manually in the ​.data​ section. (Need to be tested by changing the​ S​ and ​length​ manually.)

The signature of this procedure in a high level language would look like this:

void string_bubble_sort(char String[], int length);

Output​: for ​S​ =“​CAB​” and ​length​ = 3

CAB ABC

With the printed ​ABC

The string ​S​ MUST have ​ABC ​(,with ASCII representation; the address might be different)

NOTES​: How to print Integers and Strings/space/newline etc using ‘syscall’ https://courses.missouristate.edu/KenV ollmar/mars/Help/SyscallHelp.html

</div>
</div>
<div class="layoutArea">
<div class="column">
.data

.text

main:

# Register assignments

# $s0 = x

# Initialize registers lw $s0, x

</div>
</div>
<div class="layoutArea">
<div class="column">
x: msg1: nl: space:

</div>
<div class="column">
.word 5 .asciiz “x=” .asciiz “\n” .asciiz ” ”

</div>
</div>
<div class="layoutArea">
<div class="column">
# Print msg1

</div>
</div>
<div class="layoutArea">
<div class="column">
# Reg $s0 = x

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
li

la syscall

# Print li move syscall

# Print li

la syscall

# Exit li syscall

</div>
<div class="column">
$v0, 4 $a0, msg1

result (x) $v0,1 $a0, $s0

newline $v0,4 $a0, nl

$v0,10

</div>
<div class="column">
# print_string syscall code = 4

# print_int syscall code = 1

# Load integer to print in $a0

# print_string syscall code = 4

# exit

</div>
</div>
</div>
</div>
