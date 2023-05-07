Download Link: https://assignmentchef.com/product/solved-eml6351-project-1
<br>
<h1>1         Dynamics</h1>

Consider the two-link dynamic system

where are the angle, angular velocity, angular acceleration,

and input torque of the arm joints

<em> ,</em>

<em>m<sub>i</sub>,l<sub>i </sub></em>∈R<em>&gt;</em><sub>0 </sub>are the unknown constant mass and length of link <em>i</em>, <em>g </em>= 9<em>.</em>8 <sub>s</sub><u><sup>m</sup></u><sub>2 </sub>is gravity,

<em>c<sub>i </sub></em>= cos(<em>ϕ<sub>i</sub></em>)<em>, s<sub>i </sub></em>= sin(<em>ϕ<sub>i</sub></em>)<em>,</em>

<em>c</em><sub>12 </sub>= cos(<em>ϕ</em><sub>1 </sub>+ <em>ϕ</em><sub>2</sub>)<em>, s</em><sub>12 </sub>= sin(<em>ϕ</em><sub>1 </sub>+ <em>ϕ</em><sub>2</sub>)<em>.</em>

<h1>2         Design and Simulation</h1>

Assume <em><u>m </u></em>≤ <em>m<sub>i </sub></em>≤ <em>m</em>, <em><u>l </u></em>≤ <em>l<sub>i </sub></em>≤ <em>l</em>are known bounds on the unknown mass and length of link <em>i</em>, with

<em>m<sub>i </sub></em>= 2kg, <em>l<sub>i </sub></em>= 0<em>.</em>5m, <em><u>m </u></em>= 1kg, <em>m </em>= 3kg, and <em><u>l </u></em>= 0<em>.</em>25m, <em>l </em>= 0<em>.</em>75m. Also, assume that <em>ϕ,ϕ,</em><sup>˙ </sup><em>ϕ</em><sup>¨ </sup>are all measurable. Let the desired trajectory have a magnitude of, at a frequency of <em>f<sub>ϕ</sub></em><em><sub>d </sub></em>≜ 0<em>.</em>2Hz,

a phase shift, and bias of, such that

implying  and .

<ol>

 <li>(50 pts) Design a gradient adaptive controller that regulates the system to the desired trajectory and prove the designed controller is stable using Lyapunov-based methods. Show all your work and discuss the approach you took.</li>

 <li>(50 pts) Simulate the system tracking the provided desired trajectory. Additionally, provide the following:</li>

</ol>

1

<ul>

 <li>Plot the norm of your tracking error and filtered tracking error over time.

  <ol>

   <li>Based on these plots, how well did the designed controller track the desired trajectory?</li>

  </ol></li>

 <li>Plot the norm of your parametric error over time.

  <ol>

   <li>Based on the plots how well did you estimator approximate the unknown parameters?</li>

   <li>Plot the norm of the total input, the feedback portions of the input, and the feedforwardportions of the input and discuss how the total input behaved over time (e.g., did the input rely on feedback the majority of the time or did the feedforward portion become the majority of the input over time).</li>

  </ol></li>

 <li>Based on the plots, use quantitative and qualitative descriptions of the plots and data to brieflydiscuss whether your simulation matches your stability result, and describe anything you think would improve the result.</li>

</ul>

2