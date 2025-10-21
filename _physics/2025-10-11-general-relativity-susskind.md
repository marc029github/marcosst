---
layout: page
title: The Theoretical Minimum of General Relativity
collection: physics
date: 2025-10-19
mathjax: true
---

<script type="text/x-mathjax-config">
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],  // Explicitly enable $ for inline
      displayMath: [['$$', '$$'], ['\\[', '\\]']],  // Support both for display
      processEscapes: true,  // Handle backslashes correctly
      tags: 'ams',  // AMS extensions for advanced LaTeX
      packages: { '[+]': ['ams', 'noerrors', 'noundefined'] }  // Load required packages
    },
    options: {
      ignoreHtmlClass: 'tex2jax_ignore|mathjax_ignore|document',
      processHtmlClass: 'tex2jax_process|mathjax_process|math|output_area',
      renderActions: {
        find: [2000000, 'findMath', false],  // Prioritize math detection
        findScript: [10, 'findScript', false]  // Handle Kramdown-generated <script> tags
      }
    },
    loader: { load: ['[tex]/ams', '[tex]/noerrors'] },
    startup: {
      ready: () => {
        MathJax.startup.defaultReady();
        MathJax.typesetPromise();  // Force immediate reprocessing
      }
    }
  };
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


<style>
  body { font-family: Arial, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; }
  h1, h2 { color: #333; }
</style>


The Theoretical Minimum refers to a series of courses on various topics in physics taught by Professor Leonard Susskind at Stanford University over several years. The recordings of these lectures are available at https://theoreticalminimum.com. The aim of the series is to teach all that is necessary to truly understand modern physics—at a much deeper level than popular science books usually offer.

In my opinion, these are ideal courses for people in science and technology—non-physicists such as engineers—who want to go beyond the basic foundations they learned during their undergraduate years. They are also excellent for first- or second-year physics students who wish to gain an early glimpse into advanced physics. People in that position, like myself, do believe that one can hardly learn anything truly meaningful in science without using equations, which are essential for expressing ideas deeply and rigorously. Professor Susskind did an outstanding job with these continuing classes, for which people like myself are deeply grateful. Some of his students later decided to write books based on them. Many had already compiled and published lecture notes, so moving on to write full books seemed a natural next step.

I first read Volumes I, II and III of The Theoretical Minimum a few years ago and had been looking forward to Volume IV, devoted to General Relativity (GR).
General Relativity is a challenging subject, involving lengthy equations (even more so than quantum mechanics) and requiring a solid understanding of differential geometry. There are many excellent textbooks at various levels, but I was unable to find one that struck the right balance—something truly foundational, yet still rigorous in both mathematics and physics. During my current B.S. in Physics, I have already studied Quantum Mechanics and Hilbert spaces, as well as the fundamentals of Classical Field Theory and Special Relativity. Since then, I have often found myself puzzled—as many probably are—by how different gravity seems from other fundamental fields, both in its nature and in our understanding of it (though I might be mistaken, as I am not an expert in the field). It’s remarkable that the electromagnetic field, discovered long after gravity, is so much comprehensively (not sure if this is the right word) understood and explained.

When I finally got my copy of General Relativity: The Theoretical Minimum (Volume IV), I devoted many hours during the summer of 2025 to reading it. To reinforce my understanding, I decided to create my own notes—a kind of summary—to help me both consolidate what I’ve learned and have a quick reference for the main ideas and concepts of GR whenever I need a refresher. The document with the notes can be found in this repository at [Student Notes on General Relativity]({{ site.baseurl }}/physics/2025-10-19-Student-Notes-on-General-Relativity.pdf). A quick description of the origin of GR, which to me is the Equivalence Principle, is not in that document of notes. It is explained below.


# Equivalence Principle

The Equivalence Principle says that Gravity is in some sense the same as acceleration, although the book itself says that in the presence of a gravitational field, we can feel some phenomena that we cannot feel in the case of acceleration. Essentially we refer to the tidal forces cause by the effect of masses and energy in the spacetime.

We begin with the primed coordinates at rest relative to the stationary reference frame $x$-$y$-$z$: $z' = 0$, $x' = 0$, $y' = 0$.

![Mi imagen]({{ site.baseurl }}/physics/Elevator.png "Figure 1: Elevator and two reference frames")

The elevator then accelerates upward, with its position given by $L(t)$, where:

$$
z' = z - L(t)
$$

Given $L(t) = \frac{1}{2}gt^2$, the elevator accelerates upward with constant acceleration $g$. Differentiating with respect to time $t$

$$
\ddot{z'} = \ddot{z} - g
$$

We can write now Newton's equation:

$$
m\ddot{z'} = F - mg
$$

In the latter equation, we multiply both sides by the particle's mass, yielding $m\ddot{z}' = F$. It seems that the mass of the particle times acceleration in the primed reference frame is equal to a force minus the mass of the particle in the elevator times the acceleration $g$. It looks like the acceleration caused by a falling object in the gravity of the Earth. We can consider $g$ to be the acceleration of gravity in this example, equal to the one on the Earth. Of course, we have considered that the inertial mass of $F=ma=m\ddot{z}$ is equal to the particle mass. Note that with this assumption, the masses cancel out and then the motion of that particle in the presence of this gravitational field (equivalent to acceleration) does not depends on its mass. Based on this mental experiment, we can say that the force (ficticious $F$) of gravity mimicks the effect of gravity, which is equivalent to the effect of an acceleration. This way, you cannot differentiate between being falling in the gravitational field of the Earth or being pull out by an acceleration without any presence of gravitational field. 

This equivalence applies even to light. Consider a particle in the elevator with a lantern emitting a light ray parallel to the $x$-axis:

$$
x=ct
$$

$$
z=0
$$

$$
x'=ct
$$

$$
z'=-\frac{g}{2}t^2
$$

We can replace $t$ and write: $z'=-\frac{g}{2c^2}x'^2$. The trajectory in the primed reference frame is a parabola, it is not straight: light appears curved downwards in the presence of this acceleration. In fact, the transformation of one reference frame to the other implies a curvilinear coordinate transformation of the form:

$$
z'=z - v(t)t
$$

where $v$ is not constant, so the relation between $z'$ and $t$ is a curved. 

With this intro, we are ready to proceed to the full set of GR concepts in [Student Notes on General Relativity]({{ site.baseurl }}/physics/2025-10-19-Student-Notes-on-General-Relativity.pdf).





