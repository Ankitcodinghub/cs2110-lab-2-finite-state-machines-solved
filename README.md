# cs2110-lab-2-finite-state-machines-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Lab 2-Finite State Machines Solved](https://www.ankitcodinghub.com/product/cs2110-lab-2-finite-state-machines-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92793&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Lab 2-Finite State Machines Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Please take the time to read the entire document before starting the assignment. It is your responsibility to follow the instructions and rules.

1 Timed Lab Rules – Please Read

You are allowed to submit this timed lab starting from the moment your assignment is released until your individual period is over. You have 75 minutes to complete the lab, unless you have accommodations that have already been discussed with your professor. Gradescope submissions will remain open for several days, but you are not allowed to submit after the lab period is over. You are responsible for watching your own time. Submitting or resubmitting after your due date may constitute an honor code violation.

If you have questions during the timed lab, you may ask the TAs for clarification in a private Piazza post, though you are ultimately responsible for what you submit. The information provided in this Timed Lab document takes precedence. If you notice any conflicting information, please indicate it to your TAs.

The timed lab is open-resource. You may reference your previous homeworks, class notes, etc., but your work must be your own. Contact in any form with any other person besides a TA is absolutely forbidden. No collaboration is allowed for timed labs.

2 Overview

In this timed lab, you will implement a One-Hot State Machine in CircuitSim. This Finite State Machine will take in one 1-bit input (D), and it will output three 1-bit outputs (P, J, C). The state machine is a Moore State Machine, where your output is based solely on the current state. Diagrams and detailed instructions are provided below.

Dr. TwenTee OneTun is a roboticist and an avid nature photographer. Combining his passions, he decided to make a tiny robotic bunny with a camera to get beautiful pictures of animals in the local forest and he needs your help with the creation of his robot, the Little Cottontail MK.3. He has given you these specifications:

<ul>
<li>The robotic bunny will start out hiding.</li>
<li>If at any point, it senses daylight (D) outside, it will start foraging (State:100), activating the camera
(C) and it’s robotic jaw (J) to take photographs of nearby animals.
</li>
<li>If at any point it senses that there is no daylight outside, it will “sleep”(State:010) to conserve energy, turning off the camera and robotic jaw while turning on the low-power mode (P).</li>
<li>However, if the robotic bunny was foraging, since sleeping on the forest floor may lead to a wild animal eating the robot bunny, it will first hide and then sleep once hidden.</li>
<li>While Hidden (State:001), the bunny can and will still continue taking photographs with its camera (C) but will no longer move it’s jaw.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3 Instructions

<ol>
<li>3.1 &nbsp;State Transition Diagram
Figure 1: Transition diagram.
</li>
<li>3.2 &nbsp;Building the Circuit</li>
</ol>
Use CircuitSim to build your circuit in the tl2.sim file provided in the assignment files. Complete the circuit so that the logic matches the diagram above.

3.3 Restrictions

The input / output pins we have given you in the skeleton file must not be renamed. Do not add any additional input / output pins other than the ones we have given you. Do not rename the sub-circuit we have given you. If you have issues, check out the ”Common Errors” section below.

If you have any questions on what you may not use then assume you can’t use it and ask a TA.

You are only allowed to use the following components in CircuitSim:

• Basic logic gates (NAND, NOR, AND, OR, NOT) • Registers (for this assignment, exactly ONE).

• Wires, splitters/joiners, tunnels, constants, plexers

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4 Hints

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

• •

</div>
<div class="column">
Connect your clock and reset first.

Be careful while using the splitter component to separate your register output or combine register inputs. Remember to first set the bitsize, then the number of fan-outs and finally assign each bit to each fan-out (Bit 0 refers to the least significant bit).

Remember that due to this FSM being a One-Hot FSM, you do not need to create minimized/reduced boolean expressions and can implement your circuit with simple sum-of-products expressions.

Don’t forget to provide ALL necessary inputs to your register as well as specifying its bitsize so that it functions appropriately.

Common Errors

</div>
</div>
<div class="layoutArea">
<div class="column">
Use the autograder’s output to determine where you have gone wrong. The names of the tests you fail should usually (but not always) point you in the right direction.

Some common errors and their remedies:

<ol>
<li>Be careful that the bits on your splitters are ordered correctly. A common error is that the register inputs are combined in the opposite order, causing your state transitions to be wrong.</li>
<li>Make sure you haven’t added extra any input/output pins to your circuit. It is common to confuse constants with input pins, and probes with output pins.</li>
<li>Make sure you have not renamed input/output pins, or else the autograder won’t be able to find them.</li>
<li>Make sure you haven’t changed the name of your sub-circuit.</li>
<li>A common cause of short-circuits is two pins (on an AND gate, splitter, etc) being unintentionally connected. These are often hard to spot, since the pins are so close to each other, but if you zoom into your circuit you may find such an error and fix it.</li>
<li>Make sure the names on your tunnels match. Tunnel labels are case-sensitive, and they do not trim whitespace. If two tunnels look the same but for some reason they aren’t connecting, there may be a “space” hidden in the tunnel’s label.</li>
</ol>
6 Autograder/Grading

To run the autograder locally, navigate to the directly containing your timed lab and the tester and run the following command:

<pre>    java -jar tl2-tester.jar
</pre>
The output of the autograder is an approximation of your score on this timed lab, so that you can evaluate how much of the assignment expectations your submission fulfills. We reserve the right to change the autograder test cases before finalizing grades. Timed labs are not manually graded or reviewed by the TAs, and there will not be opportunities for partial credit beyond the autograder. Submissions that are not runnable will receive a 0.

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
