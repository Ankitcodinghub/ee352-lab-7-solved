# ee352-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [EE352 Lab 7 Solved](https://www.ankitcodinghub.com/product/ee352-lab-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94349&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE352 Lab 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
In this week, we mainly discuss the Phase Modulation (PM) and review the Frequency Modulation (FM) that you implemented in the last week’s experiment. As you already know, angle modulation is a way of modulating a sinusoidal carrier wave just like the amplitude modulation. In this method of modulation, the phase angle of the carrier wave is varied according to a baseband signal which is called as message signal. The two forms of the angle modulation which are the phase modulation and the frequency modulation are closely related in that the properties of the one can be derived from those of the other. Therefore, you will demonstrate both the FM and PM signals in the first part. Then, you will show the PM signals for different phase sensitivity values to visualize the effect of this parameter.

The second part of the experiment deals with the demodulation of the phase modulated signal. Demodulation of the PM signal can be done by extracting instantaneous phase using Hilbert transform. Hilbert transform is a linear operation which has a number of area of utilization. One of them is the generation of analytic signal or pre-envelope. Using the Hilbert transform, a complex-valued analytic signal x(t) can be obtained from a real-valued signal s(t). The analytic signal x(t) is directly related to the Hilbert transform of s(t) as well as s(t) signal itself. For the demodulation, phase modulated signal is transformed into the analytic signal. Then, the instantaneous phase is extracted from that signal to recover the message.

Please learn about the MATLAB functions sawtooth(.), cumsum(.), hilbert(.), abs(.), angle(.), unwrap(.) and phase(.) before doing the labwork given below.

2 Labwork

</div>
</div>
<div class="layoutArea">
<div class="column">
2.1

a.

</div>
<div class="column">
Angle Modulation (FM &amp; PM)

Consider the triangular message signal, m(t) which is shown in Figure 1. Construct m(t) by using the built-in function sawtooth(.) where the sampling frequency is Fs = 2 kHz.

Hint: Determine the signal parameters from the figure and pay attention that m(t) = 0 for t = 0.

</div>
</div>
<div class="layoutArea">
<div class="column">
b.

</div>
<div class="column">
Figure 1: Triangular message signal, m(t)

The frequency modulated (FM) signal is defined in (1) where the carrier signal is c(t) = cos(2πfct). Construct sF M (t) by using the built-in function cumsum(.) for the carrier frequency fc = 100 Hz and the frequency sensitivity kf = 80 Hz/V.

􏰀􏰂t􏰁

</div>
</div>
<div class="layoutArea">
<div class="column">
sF M (t) = cos 2πfct + 2πkf

1

</div>
<div class="column">
m(λ)dλ (1)

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EE 352 – Lab 7: Phase Modulation (PM)

</div>
</div>
<div class="layoutArea">
<div class="column">
c. The phase modulated (PM) signal is defined in (2) where the carrier signal is c(t) = cos(2πfct). Construct sP M (t) for the carrier frequency fc = 100 Hz and the phase sensitivity kp = 2π rad/V.

sP M (t) = cos􏰃2πfct + kpm(t)􏰄 (2)

<ol start="4">
<li>Plot m(t), sF M (t) and sP M (t) on the same figure by using 3 × 1 subplot.</li>
<li>Comment on the relationship between FM and PM signals in your reports.</li>
<li>Construct sPM2(t) for kp = 3π rad/V and sPM3(t) for kp = 4π rad/V. Plot sPM(t), sPM2(t) and sP M3 (t) on the same figure by using 3 × 1 subplot.</li>
<li>Comment on the effect of different kp values to phase modulation in your reports.</li>
</ol>
2.2 Demodulation of PM Signal

<ol>
<li>Read the preliminaries above carefully to understand the concept of analytic signals. Then, follow the block diagram of the demodulation of PM signal shown in Figure 2.
Figure 2: Demodulation of PM signal.
</li>
<li>First, obtain the analytic signal xP M (t) using the Hilbert Transform of sP M (t). Remember that sP M (t)
was constructed for kp = 2π rad/V.
</li>
<li>Plot the magnitude of the frequency responses of m(t), sP M (t) and xP M (t) on the same figure by using
3 × 1 subplot.
</li>
<li>Using xPM(t), extract the instantaneous phase θi(t) and detect the message signal as mˆ(t).</li>
<li>Apply the steps 2.2.b and 2.2.d for sP M3 (t) to obtain the demodulated signal mˆ 3(t).</li>
<li>Plot m(t), mˆ (t) and mˆ 3(t) on the same plot by using hold on command. Please insert a legend.</li>
<li>Comment on the relationship between message signal and demodulated signals and discuss the effect of different kp values to demodulation. Put your comments to your reports.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
