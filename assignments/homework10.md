---
layout: homework
use_math: true
title: Homework 10 (Due. Apr. 5)
---

## 1. Different kinds of conductors

In Griffiths (and in class), we derived equations for EM waves in conductors, assuming a "good conductor." Interestingly, it turns out that the formulas we got can be pushed a good deal further than you might naively expect, into regimes where $\sigma$ is not so large ("poor conductors.") In this case, you will need to use Griffiths more careful results for the real and imaginary parts of the k vector and work with those.

1. Based on the above comments, show that the skin depth for a "poor conductor" (i.e., $\sigma \ll \varepsilon \omega$) is $d \approx ?? \sqrt{\varepsilon/\mu}$, independent of frequency or wavelength. Work out what the "??" is in this equation. (Also, check the units of your answer explicitly, please!)
2. Show that the skin depth for a "good conductor" (i.e., $\sigma \gg \varepsilon \omega$) is $d = \lambda/??$, where $\lambda$ is the wavelength in the conductor. (Work out the ?? in that formula.) Find the skin depth for microwaves in Cu ($f$ = 2.5 GHz). Briefly, how do you interpret that answer physically?
3. About how thick does aluminum foil have to be, to be optically opaque? Comment briefly.
4. For biological tissues (like skin), $\varepsilon$ and $\sigma$ depend on frequency, you can't use their free space values. But, $\mu$ on the other hand is close to its free space value. At microwave frequencies (say, about 2.5 GHz), their values are $\sim$ $\varepsilon =47 \varepsilon_0$, and $\sigma = 2.2 \Omega^{-1}m^{-1}$. Is skin (at this frequency) the "good conductor" or "poor conductor" case, or neither? Evaluate the skin depth for microwaves hitting your body.
5. If the EM wave from part 4 (e.g. from a radar station) hits your body, what fraction of the incident power do you absorb? (Hint: think about "R" first, then you can get "T" easily!)
6. Let's think about contacting submarines by radio. For low frequency radio waves (say, $f$=3 kHz) estimate the skin depth in the sea, and comment on the feasibility/issues of such radio communication. What is the wavelength of this same radio wave in free space, by the way?
(Hint: Treating seawater as like a human body is ok for this one- just use the given values from part 4 as needed. But, as mentioned there, in reality they'll be different at this very different frequency and slightly different material. Small bonus credit if you can find more appropriate values, and give the reference!)

## 2. Wave Packets

We keep saying that you can always sum up plane waves to get real wave packets. Let's try it! Consider a localized wavepacket that satisfies the one-dimensional wave equation from a sum of sinusoidal waves using Fourier's integral method:

$$f(x,t) = \int_{-\infty}^{\infty} A(k)e^{ik(x-ct)}dk$$

1. Show that the $f(x,t)$ satfies the one-dimensional wave equation with wave speed, $c$.
2. Assume that $A(k)$ is given by the a Gaussian distribution centered at some positive wavevector $k_0$:
$$A(k)=\dfrac{1}{\sqrt{2 \pi \sigma^2}}\exp\left(-\dfrac{(k-k_0)^2}{2\sigma^2}\right)$$
Sketch this function, Roughly what range of wavevectors $\Delta k$ contribute signficantly to the wave packet?
3. Calculate $f(x,t)$ from the above $A(k)$. There is a famous and handy Gaussian integral that can be helpful here that works for any $z$ even complex ones! $$\int_{-\infty}^{\infty} \exp\left(-\dfrac{q^2y^2}{2}+zy\right)dy = \sqrt{\dfrac{2\pi}{q^2}}\exp\left(\dfrac{z^2}{2q^2}\right)$$
4. Describe $f(x,t)$ physically as best you can. How is the $x$-width, $\Delta x$ of the "wavepacket" related to the $k$-width $\Delta k$? Does this relationship between $\Delta x$ and $\Delta k$ remind you of anything from quantum mechanics (PHY 215 or 471)?
5. Pick a visible wavelength, and plot, using Jupyter, a Gaussian pulse that lasts 1 femtosecond. (When I say plot, I'm thinking of $Re[f(x,t=0)]$, and then think about what happens as time goes by) Try to get as many details reasonably correct as you can.

**As usual, you will turn part 5 in using your GitHub repo**

## 3. Paired Project Problem

1. Read the feedback that you received on your figure/models and think about how you and your partner are going to work through these details.
2. Project work - Provide some sample calculations and figures produced by your code. This can be a notebook (Jupyter), but the work needs to be explained inline (i.e., what are you doing and why?). This is the work that is the meat of your original contribution. It need not be complete yet.
3. Self-reflection - Think about how the project is going and how you are both contributing. Write out a document for the last couple of weeks worth of work inclduing this one that describes: Who did what? Hoes does it feel like the contributions for the members of your pair are equal? Regarding the project specifically, what questions do you need to answer to continue to move forward and what help do you need from me or others?

You will turn in both your "notebook" and your self-reflection using the same GitHub repository you started for Project 2. **Make sure that you sync your repository first to get the new feedback!**


## 6. Paired Project Problem - Starting your pair project

This second project can (but doesn't have to) build on the project you just complted. It is a team project that you will complete with a partner. This project is meant to mimic the common practice of poster preparation and presentation. In a nutshell, you will conduct an original modeling project where you analytically and computationally model some E&M phenomenon of your choosing, prepare a poster of the project, and present it to your classmates and me. In working on this project, you will be trying to answer the following questions:

* What is the area of E&M that you are doing research on?
* What are the questions that you are trying to answer about this area?
* What theoretical models can be used to answer those questions?
* What analytical and computational work did you do to answer those questions?
* What were the resulting predictions that your work produced?
* What are the limitations of what you have done? * What are some remaining open questions?
* What did each member of your pair contribute?

There will be six homework problems to help scaffold your work and poster development. In this first homework problem, you and your partner will write up a single document that answers the following questions:

* Who are the partners in this team?
* What are you and your partner proposing to do?
* What area of E&M will you be conducting original calculations for?
* What source material are you drawing from?
* What has been done so far and what are you going to do? It's ok if it's a solved problem, but you will need to reproduce what has been done and extend it beyond what your reference material offers.

**As usual, you will turn in this document using GitHub.**

## 4. Paired Project Problem - Planning your project

1. Read the feedback that you received on your plan and think about how you and your partner are going to work through your new plan.
2. Project work - Provide a detailed explanation of the models and theoretical calculations needed to set up your work. The produce that you produce for this should be presented as a "graphic" that would appear in a poster under "background or model."
3. Self-reflection - Think about how the project is going and how you are both contributing. Write out a document for the last couple of weeks worth of work inclduing this one that describes: Who did what? Hoes does it feel like the contributions for the members of your pair are equal? Regarding the project specifically, what questions do you need to answer to continue to move forward and what help do you need from me or others?

**Each team will turn in a single repository, so put your work there.**

## 3. Radiation pressure

On earth, the time-averaged flux of electromagnetic energy ($\langle S \rangle$) from the sun is 0.14 $\text{watt/cm}^2$. Consider steady sunlight hitting 1 $\text{m}^2$ of Earth: picture an imaginary box (containing streaming sunshine) striking this area, with a "box height" of 1 light-second. There is a certain amount of momentum stored in that box, and in one second, ALL that momentum will strike the 1 $\text{m}^2$ area.

1. Assuming the EM wave is absorbed (not reflected), what force does that work out to? How does the radiation pressure from this light compare to atmospheric air pressure, Comment! If the earth reflected the sunlight, how would that affect the radiation pressure (qualitatively)?
2. What is the net force on the Earth from this radiation pressure, assuming the Earth absorbs all the EM energy? Compare this force to the gravitational force of the sun on the earth, and comment.
3. If I made a 100 kg spacecraft with a 10,000 $\text{m}^2$ large black sail to absorb the sunlight and propel me away from the sun, what would its acceleration be? (This is called a solar sail, and there are serious proposals to build such a craft!) What are some advantages and disadvantages over conventional spacecraft?
