# hy330-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [HY330 Assignment 3 Solved](https://www.ankitcodinghub.com/product/hy330-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91848&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;HY330 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
General Information

The goal of this assignment is to become familiar with two basic modulation schemes, FSK and AM, PSK and QAM. You will be also implement your first GNU Radio block.

Exercise 1

In this exercise you will investigate the AM modulation.

<ol>
<li>Create a new flowgraph that has sampling rate of 192 KSPS (192000 samples/sec).</li>
<li>Start your flowgraph with a random source block, that produces samples in the range of [0,1] with byte data type. This will be your source bit stream.</li>
<li>Consider that our telecommunication scheme has a target bitrate of 9600 bits/sec. Use the Repeat block to increase the duration of every sample from the random source block.</li>
<li>Plot the resulting signal at a time sink with the target sampling rate equal to 192 KSPS.</li>
<li>The [0,1] range is very convenient in the digital domain, but in most cases it is problematic for signal processing. Apply the proper operations on the signal and convert it on the range [-1, 1]. A bit with value 0 should correspond to a -1 signal amplitude. Use the time sink of the previous step to justify your result.</li>
</ol>
Now you are going to modulate this signal using Amplitude modulation. The mathe- matical formula for the AM is:

[]

y(t)=A 1+μx(t) cos(2πfct)

where y(t) is the modulated signal, A the amplitude, μ the modulation index, x(t) the

input data signal with the proper symbol duration and fc the carrier frequency.

<ol start="6">
<li>Modulate the signal that you have already constructed with AM using the following
parameters:

• A=1

• μ=0.8

• fc=10kHz

Report a screenshot of the modulated signal.
</li>
<li>Research the bibliography and report what is the modulation index. Play with dif- ferent values and report what do you observe.
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="8">
<li>During your experiments you may observe that there are too many spurious emis- sions on the resulting spectrum. Report possible reasons for this.</li>
<li>Try to reduce the number of spurious by applying pulse shaping and/or other kind of filtering. You my find useful an existing pulse shaping flowgraph that is located at the examples directory.</li>
</ol>
Exercise 2

In this exercise you will improve the performance of the naive FM modulator that we created during the class.

<ol>
<li>Open the simplified_fsk.grc flowgraph. Make all the proper modifications, in order the sampling rate to be 192 KSPS and the bitrate 1200.</li>
<li>Try to improve the RF performance of the FSK modulator (reduce the spurious emissions) by applying pulse shaping and/or filtering.</li>
<li>Compare the resulting bandwidth with the bandwidth of a proper FSK modulator, like GNU Radio provides (frequency_mod block). What do you observe?</li>
</ol>
Exercise 3

In this exercise you will implement your first GNU Radio block, providing the implementa- tion of a modulator that supports various modulations schemes (BPSK, QPSK, 16-QAM).

<ol>
<li>First create a part of the flowgraph that reads data from a file and splits the byte stream into a stream of K bits per byte. K is the number of bits per constellation point, depending the modulation scheme of the scenario. You can use the existing GNU Radio blocks for byte splitting.</li>
<li>Using the gr_modtool create a block with the name constellation_mapping. This block has a byte input stream and a complex output stream. For every byte of K bits it produces a complex number that corresponds to a constellation point of the appropriate modulation scheme. The block takes as argument the number of K bits that each constellation point carries. This number can be used to identify the modulation scheme that should be used, depending on the table below.
K Modulation
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 4

</div>
<div class="column">
BPSK

QPSK 16-QAM

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
The constellation points for every modulation scheme are depicted in Figures 1, 2 and 3. Using the QT Constellation sink, provide a screen-shot of the constellation for each

modulation scheme.

3. You may observe that the maximum IQ amplitude of each modulation scheme is dif- ferent. This means that the mean energy of each modulation scheme is different. In general this is not desirable. For this reason, perform normalization at the constel- lation points of each modulation scheme. The normalization factors can be retrieved from the table below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Modulation

BPSK

QPSK 16-QAM

</div>
<div class="column">
Normalization factor

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰈

</div>
</div>
<div class="layoutArea">
<div class="column">
1/ 2

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰈

</div>
</div>
<div class="layoutArea">
<div class="column">
1/ 10

</div>
</div>
<div class="layoutArea">
<div class="column">
Again, provide a screen-shot that shows the constellation of each modulation scheme. Discuss possible reasons for a system to have the same mean energy for all modula- tion schemes.

Figure 1: BPSK constellation points

Figure 2: QPSK constellation points

3

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 3: 16-QAM constellation points

</div>
</div>
</div>
