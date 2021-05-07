---
title: 'Arcade Simplex: Applying Trigonometry to 3D Arcade Video Games'
tags:
  - javascript
  - babylon.js
  - videogames
  - trigonometry
  - 3d videogames
authors:
  - name: Nick V. Flor^[Corresponding author]
    orcid: 0000-0002-5162-9277
    affiliation: 1 # (Multiple affiliations must be quoted)
affiliations:
 - name: Nick V. Flor, Associate Professor, University of New Mexico
   index: 1
date: 01 May 2021
bibliography: paper.bib
---

# Background

In the Fall of 2017, as part of the Freshman Learning Communities program at the University of New Mexico, I taught a class to incoming freshmen on Internet Memes & Digital Media (MGMT190, hereafter “Memes Class”) in the business school, which was paired with Computer Programming Fundamentals (CS151L, hereafter “Programming Class”) in the engineering school.

The goal of the paired classes was to get students to apply the concepts in Programming Class to Memes Class. The first week of class, I asked students how they would like to apply the programming skills they learned. An overwhelming majority indicated they would like to try and create a new kind of meme based on simple video games. 

`ArcadeSimplex` was the codebase I created to help students — with neither programming nor game development experience — to develop their video game memes.

# Summary

A 3D Video Game Learning Tutorial Based on ProfessorF's Arcade Simplex Theory

This is teaching code. The goal is not _efficient_ code, per se, but _easy-to-understand_ code. All game pieces are based on simple polygons, but it is easy to replace them with more sophisticated models. The use of polygons, however, allows game programmers to focus on learning the basics of the code, rather than being distracted by model code. 

The master contains the base code.  Each branch is a variation that builds functionality on top of the base code. 

There are 9 branches:

1. ArcadeSimplexBase -- this is always merged into the master, and contains bug fixes to the main code
2. VFollowCam -- a follow-behind and follow--top camera
3. VObstacles -- block obstacles, which stop monsters, bullets, and the hero
4. VMonstersFiring -- monsters firing when the hero gets too close
5. VPowerPellets -- the picking up of pellets before firing
6. VThreeMissiles -- firing three missiles at once
7. VSplitHitMissiles -- monsters exploding into richocheting missiles
8. VNormalExplosion -- monsters exploding before when hit
9. VInfiniteMonsters -- after clearing a level, the number of monsters doubles; this continues until the player dies 

# Statement of need

Learning computer programming is notoriously difficult but a motivated student will usually succeed despite bad conditions in the teaching or in the tools that constitute the learning environment (Brito and de Sá-Soares, 2014).

One way to motivate students is to have them apply the material to solve problems they are interested in, rather than the typical abstract problems, e.g., the rainfall problem (Johnson and Soloway, 1985), given to intro to programming students:

`Gala` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has already been
used in a number of scientific publications [@Pearson:2017] and has also been
used in graduate courses on Galactic dynamics to, e.g., provide interactive
visualizations of textbook material [@Binney:2008]. The combination of speed,
design, and support for Astropy functionality in `Gala` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia* mission
[@gaia] by students and experts alike.

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$

You can also use plain \LaTeX for equations
\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}
and refer to \autoref{eq:fourier} from text.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub without a preferred
citation) then you can do it with the example BibTeX entry below for @fidgit.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

This material is based partly upon work supported by the National Science Foundation (NSF)
under both ECCS - 1231046 and CMMI - 1635334. Any opinions, findings, and conclusions or 
recommendations expressed in this material are those of the author and do not necessarily
reflect the views of the NSF.

# References
