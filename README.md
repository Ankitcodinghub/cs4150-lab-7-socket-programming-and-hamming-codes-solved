# cs4150-lab-7-socket-programming-and-hamming-codes-solved
**TO GET THIS SOLUTION VISIT:** [CS4150 Lab 7-Socket Programming and Hamming Codes Solved](https://www.ankitcodinghub.com/product/cs4150-lab-7-socket-programming-and-hamming-codes-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94561&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4150 Lab 7-Socket Programming and Hamming Codes Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (6 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
(Socket Programming and Hamming Codes)

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Virtual network for this lab has 3 VMs namely h1 (192.168.1.1) , h2 (192.168.1.2), and h3 (192.168.1.3).

On machine h1 write a program called client that takes two argument S and m; the first argument is a string, and the second argument is an integer. The program should output the binary (8-bit per character) of the string S. The program should then frame and code this data using a (m + r, m) Hamming code (r should be the least possible for the given number of message bits m). Each Hamming code should be sent as a UDP packet to port X of h2, where X ∈ [8560,8570]. h2 will introduce a random 1-bit error in each Hamming code it receives and will then send the modified code to port Y of h3.

On h3, write a program called server that accepts codes with 1-bit error sent by h2, corrects the error, assembles all the corrected codes together to obtain string S, prints S with a newline and waits for the next string. The division of marks for this lab is as follows.

<ol>
<li>(a) &nbsp;Sending a binary string from h1 and receiving the 1-bit error binary string at h3. [25]</li>
<li>(b) &nbsp;Encoding and correcting errors using Hamming codes. [25]</li>
<li>(c) &nbsp;Padding, pre-coding and framing. [25]</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
(d) Encoding S as a binary character array at h1 and recovering it at h3, printing S along with a new line at h3 and waiting for the next string.

</div>
</div>
</div>
