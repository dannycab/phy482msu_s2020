---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

Somewhere in space a magnetic field is changing with time, there are no other sources of electric field field anywhere. In this case, can we define a potential difference between two points?

1. Yes, we can always do this
2. Yes, but only if we define the specific path as well
3. No, the story is more complicated than A or B.
4. No, whenever $\nabla \times E \neq 0$, the concept of potential breaks down
5. More than one of these

Note:
* Correct Answer: E
* It's C and D because we can't define V in the same way as before.

</section>

<section data-markdown>

The current $I_1$ in loop 1 is increasing. What is the direction of the induced current in loop 2, which is co-axial with loop 1?

<img src="./images/mutual_coil_1.png" align="center" style="width: 300px";/>

1. The same direction as $I_1$
2. The opposite direction as $I_1$
3. There is no induced current
4. Need more information

Note:
* Correct Answer: B
* The magnetic field due to loop 1 is increasing and points up, which creates an electric field that curls around the negative increasing direction (i.e., opposite the direction loop 1). Or you can think lenz's law; the magnetic flux is increasing through loop 2.
</section>

<section data-markdown>

The current $I_1$ in loop 1 is increasing. What is the direction of the induced current in loop 2, which lies in the same plane as loop 1?

<img src="./images/mutual_coil_2.png" align="center" style="width: 500px";/>

1. The same direction as $I_1$
2. The opposite direction as $I_1$
3. There is no induced current
4. Need more information

Note:
* Correct Answer: A
* Similar to the previous one, but the magnetic field now points down (think magnetic dipole for the shape of the field).
</section>

<section data-markdown>

The current $I_1$ in loop 1 is decreasing. What is the direction of the induced current in loop 2, which lies in a plane perpendicular to loop 1 and contains the center of loop 1?

<img src="./images/mutual_coil_3.png" align="center" style="width: 400px";/>

1. The same direction as $I_1$
2. The opposite direction as $I_1$
3. There is no induced current
4. Need more information

Note:
* Correct Answer: C
* There's basically no flux, because the magnetic field points down and the loop face is perpendicular to that magnetic field.
</section>

<section data-markdown>

Two flat loops of equal area sit in a uniform field $\mathbf{B}$ which is increasing in magnitude. In which loop is the induced current the largest? (The two wires are insulated from each other at the crossover point in loop 2.)

<img src="./images/mutual_coil_4.png" align="center" style="width: 600px";/>

1. Loop 1
2. Loop 2
3. They are both the same
4. Not enough info

Note:
* Correct Answer: A
* Loop 2 will have roughly no current because the orientation of the crossover is such that current would try to run CW in both lobes.

</section>

<section data-markdown>

<img src="./images/solenoid_w_loop_mutual.png" align="right" style="width: 300px";/>

A loop of wire 1 is around a very long solenoid 2.

<img src="./images/phi_1_eqn.png" align="left" style="width: 200px";/>
= the flux through loop 1 due to the current in the solenoid

<img src="./images/phi_2_eqn.png" align="left" style="width: 200px";/>
= the flux through the solenoid due to the current in loop 1

Which is easier to compute?
1. $M_{12}$
2. $M_{21}$
3. equally difficult to compute

Note:
* Correct Answer: A
* The geometry of the first one is easier. This means we can choose to solve the easy problem as M12 = M21.

</section>

<section data-markdown>

A long solenoid of cross sectional area, $A$,  length, $l$, and number of turns, $N$, carrying current, $I$, creates a magnetic field, $B$, that is spatially uniform inside and zero outside the solenoid. It is given by:

<img src="./images/B_solenoid.png" align="center" style="width: 700px";/>

1. $B = \mu_0 {N^2}/{l}$
2. $B = \mu_0 ({N^2}/{l})I$
3. $B = \mu_0 ({N}/{l})I$
4. $B = \mu_0 ({N^2}/{l})AI$

Note:
* Correct Answer: C
* This is meant to be a reminder of the field of a solenoid with N turns and length l; recall it's turns per length that matter N/l.
</section>

<section data-markdown>

A long solenoid of cross sectional area, $A$,  length, $l$, and number of turns, $N$, carrying current, $I$, creates a magnetic field, $B$, that is spatially uniform inside and zero outside the solenoid. The self inductance is:

<img src="./images/B_solenoid_2.png" align="center" style="width: 700px";/>

1. $L=\mu_0{N^2}/{(IA)}$
2. $L=\mu_0({N}/{l})A$
3. $L=\mu_0({N^2}/{l^2})A$
4. $L=\mu_0({N^2}/{l})A$

Note:
* Correct Answer: D
* This is just flux divided by current; but the flux through the whole solenoid is N times the flux through one loop.

</section>

<section data-markdown>

<img src="./images/2_loops_in_B.png" align="right" style="width: 400px";/>
Loop 1 sits in a uniform field B which is increasing in magnitude. Loop 2 has the SAME LENGTH OF WIRE looped (coiled) to make two (smaller) loops.
How do the induced EMFs compare?


1. EMF(1)=4 EMF(2)
2. EMF(1) = 2 EMF(2)
3. They are both the same.
4. EMF(2)= 4 EMF(1)
5. EMF(2) = 2 EMF(1)

Note:
* Correct Answer: B
* Reduce A by 4, Loops up by 2
</section>

<section data-markdown>

The switch is closed at $t=0$. What can you say about $I(t=0+)$?

<img src="./images/RL_circuit.png" align="right" style="width: 400px";/>

1. Zero
2. $V_0/R$
3. $V_0/L$
4. Something else!
5. ???

Note:
* Correct Answer: A
* Just after the switch is closed; the inductor has seen a huge dI/dt

</section>

<section data-markdown>

<img src="./images/RL_circuit.png" align="right" style="width: 300px";/>

The switch is closed at $t=0$.
Which graph best shows $I(t)$?

E) None of these (they all have a serious error!)

<img src="./images/RL_graphs.png" align="center" style="width: 600px";/>


Note:
* Correct Answer: B
* The current grows as the inductor sees less changes, eventually saturating.

</section>

<section data-markdown>

<img src="./images/RL_circuit.png" align="right" style="width: 300px";/>

The switch is closed at $t=0$.
What can you say about the magnitude of $\Delta V$(across the inductor) at
$(t=0+)$?

1. Zero
2. $V_0$
3. $L$
4. Something else!
5. ???

Note:
* Correct Answer: B
* There's no current, so the potential drop is entirely across the inductor

</section>

<section data-markdown>

For the RL circuit with driving voltage of $V(t) = V_0 \cos (\omega t)$, we found a solution for the current as a function of time, with $I=0$ at $t=0$,

$$I(t) = a \cos(\omega t + \phi) - a\cos(\phi) e^{-Rt/L}$$

where $a = \frac{V_0}{\sqrt{R^2+L^2\omega^2}}$ and $\phi = \tan^{-1}(-L\omega/R)$. What happens to the current when $\omega \rightarrow 0$?

1. Current is essentially zero, for all time
2. Current dies off completely, eventually goes to zero
3. Eventually, current is constant, $V_0/R$
4. It depends
5. ???

Note:
* Correct answer: C
* It's just the DC result, the current saturates as before

</section>

<section data-markdown>

For the RL circuit with driving voltage of $V(t) = V_0 \cos (\omega t)$, we found a solution for the current as a function of time, with $I=0$ at $t=0$,

$$I(t) = a \cos(\omega t + \phi) - a\cos(\phi) e^{-Rt/L}$$

where $a = \frac{V_0}{\sqrt{R^2+L^2\omega^2}}$ and $\phi = \tan^{-1}(-L\omega/R)$. What happens to the current when $\omega \rightarrow \infty$?

1. Current is essentially zero, for all time
2. Current dies off completely, eventually goes to zero
3. Eventually, current is constant, $V_0/R$
4. It depends
5. ???

Note:
* Correct answer: A
* The fast changes cause very large dI/dt, so the inductor continues to resist current flow

</section>



<section data-markdown>

Which point below best represents $4e^{i3\pi/4}$ on the complex plane?

<img src="./images/complex_numbers_graph.png" align="center" style="width: 600px";/>

Note:
* Correct Answer: D
* Graph it out with the the 3pi/4 rotation

</section>

<section data-markdown>

<img src="./images/RLC.png" align="right" style="width: 400px";/>
What is the total impedance of this circuit, $Z_{total}$?

1. $R + i\left(\omega L + \frac{1}{\omega C}\right)$
2. $R + i\left(\omega L - \frac{1}{\omega C}\right)$
3. $\frac{1}{R} + \frac{1}{i\omega L} + {i \omega C}$
4.  $\dfrac{1}{\frac{1}{R} + \frac{1}{i\omega L} + {i \omega C}}$
5. None of these

Note:
* Correct Answer: B
* Just use the definitions of each and add in seriesjs

</section>
