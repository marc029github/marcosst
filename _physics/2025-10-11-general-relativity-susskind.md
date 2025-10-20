---
layout: page
title: The Theoretical Minimum of General Relativity
collection: physics
date: 2025-10-19
---

The Theoretical Minimum refers to a series of courses on various topics in physics taught by Professor Leonard Susskind at Stanford University over several years. The recordings of these lectures are available at https://theoreticalminimum.com. The aim of the series is to teach all that is necessary to truly understand modern physics—at a much deeper level than popular science books usually offer.

In my opinion, these are ideal courses for people in science and technology—non-physicists such as engineers—who want to go beyond the basic foundations they learned during their undergraduate years. They are also excellent for first- or second-year physics students who wish to gain an early glimpse into advanced physics. People in that position, like myself, do believe that one can hardly learn anything truly meaningful in science without using equations, which are essential for expressing ideas deeply and rigorously. Professor Susskind did an outstanding job with these continuing classes, for which people like myself are deeply grateful. Some of his students later decided to write books based on them. Many had already compiled and published lecture notes, so moving on to write full books seemed a natural next step.

I first read Volumes I, II and III of The Theoretical Minimum a few years ago and had been looking forward to Volume IV, devoted to General Relativity (GR).
General Relativity is a challenging subject, involving lengthy equations (even more so than quantum mechanics) and requiring a solid understanding of differential geometry. There are many excellent textbooks at various levels, but I was unable to find one that struck the right balance—something truly foundational, yet still rigorous in both mathematics and physics. During my current B.S. in Physics, I have already studied Quantum Mechanics and Hilbert spaces, as well as the fundamentals of Classical Field Theory and Special Relativity. Since then, I have often found myself puzzled—as many probably are—by how different gravity seems from other fundamental fields, both in its nature and in our understanding of it (though I might be mistaken, as I am not an expert in the field). It’s remarkable that the electromagnetic field, discovered long after gravity, is so much comprehensively (not sure if this is the right word) understood and explained.

When I finally got my copy of General Relativity: The Theoretical Minimum (Volume IV), I devoted many hours during the summer of 2025 to reading it. To reinforce my understanding, I decided to create my own notes—a kind of summary—to help me both consolidate what I’ve learned and have a quick reference for the main ideas and concepts of GR whenever I need a refresher. The document with the notes can be found in this repository at [Student Notes on General Relativity]({{ site.baseurl }}/physics/2025-10-19-Student-Notes-on-General-Relativity.pdf). A quick description of the origin of GR, which to me is the Equivalence Principle, is not in that document of notes. It is explained below.


# Equivalence Principle

The Equivalence Principle says that Gravity is in some sense the same as acceleration, although the book itself says that in the presence of a gravitational field, we can feel some phenomena that we cannot feel in the case of acceleration. Essentially we refer to the tidal forces cause by the effect of masses and energy in the spacetime.

Supongamos un sistema de referencia estacionario x-y-z, por ejemplo la superficie de la tierra, y otro sistema x'-y'-z' pegado al suelo de un ascensor como en la figura siguiente.
![Mi imagen]({{ site.baseurl }}/physics/Elevator.png "Figure 1: Elevator and two reference frames")

We start with z'=0, x'=0, y'=0 with respect to the stationary reference frame x-y-z. The elevator will start moving upwards, with its new position being $L(t)$ and:
$z' = z - L(t)$, where  $L(t) = \frac{1}{2}gt^2$, that it, it is moving up with acceleration $g$. If we calculate the derivatives with respect to $t$:

$$
\ddot{z'} = \ddot{z} - g
$$

We can write now Newton's equation:

$$
m\ddot{z'} = F - mg
$$

In this latter equation we have multiplied both sides by the mass of the particle and have considered $m\ddot{z} = F$. It seems that the mass of the particle times acceleration in the primed reference frame is equal to a force minus the mass of the particle in the elevator times the acceleration $g$. It looks like the acceleration caused by a falling object in the gravity of the Earth. We can consider $g$ to be the acceleration of gravity in this example, equal to the one on the Earth. Of course, we have considered that the inertial mass of $F=ma=m\ddot{z}$ is equal to the particle mass. Note that with this consideration masses cancel out and then the motion of that particle in the presence of this gravitational field (equals acceleration) does not depends on its mass. Based on this mental experiment, we can say that the force (ficticious $F$) of gravity mimicks the effect of gravity, which equivalent to the effect of an acceleration. This way, you cannot differentiate between being falling in the gravitational field of Earth or being pull out by an acceleration without any presence of a gravitational field. 

This effect applies also to light. Imagine the particle has a lintern and emits a ray of light parallel to axis $x$, then:

$$
x=ct
z=0
x'=ct
z'=-\frac{g}{2}t^2
$$

We can replace $t$ and write: $z'=-\frac{g}{2c^2}x'^2$. The trajectory in the primed reference frame is a parabola, not straight: light is bending in the presence of this acceleration. In fact, the transformation of one reference frame to the other implies a curvilinear coordinate transformation of the form:

$$
z'=z - v(t)t
$$

where $v$ is not constant, so the relation between $z'$ and $t$ is a curved. 

With this intro, we are ready to move on to the details in [Student Notes on General Relativity]({{ site.baseurl }}/physics/2025-10-19-Student-Notes-on-General-Relativity.pdf).





