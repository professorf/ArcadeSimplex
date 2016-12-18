# ArcadeSimplex
A 3D Video Game Learning Tutorial Based on ProfessorF's Arcade Simplex Theory

This is teaching code. The goal is not _efficient_ code, per se, but _easy-to-understand_ code. All game pieces are based on simple polygons, but it is easy to replace them with more sophisticated models. The use of polygons, however, allows game programmers to focus on learning the basics of the code, rather than being distracted by model code. 

The master contains the base code.  Each branch is a variation that builds functionality on top of the base code. 

There are 9 branches:

1. ArcadeSimplexBase -- this is always merged into the master, and contains bug fixes to the main code
2. VFollowCam -- a follow-behind and follow--top camera
3. VObstacles -- block obstacles, which stop monsters, bullets, and the hero
4. VMonstersFiring -- monsters firing when the hero gets too close
5. VPowerPellets -- the picking up of pellets before firing
6. VThreeMissiles -- firing three missies at once
7. VSplitHitMissiles -- monsters exploding into richocheting missiles
8. VNormalExplosion -- monsters exploding before when hit
9. VInfiniteMonsters -- after clearing a level, the number of monsters doubles; this continues until the player dies 
