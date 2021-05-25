# ArcadeSimplex
A codebase for learning how to create 3D video games on Linux, Mac, and Windows — Based on ProfessorF's Arcade Simplex Theory.

## Introduction
ArcadeSimple is a codebase for learning how to create 3D games using the CAT strategy (Copying And Tweaking). The codebase assumes both minimal math knowledge and minimal software requirements. To create their own games learners need only an understanding of basic alegbra, a text editor, a web browser, and the Babylon.js 3d library. The _git_ app is also recommended for checking out different codebase branches. 

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

## Required and Recommended Software 
ArcadeSimplex requires a web browser, a text editor, and the Babylon.js 3D library. Most learners already have a web browser and a text editor. Thus, at minimum one need only download the Babylon.js 3D library to start building games. However, the following specific software is recommended:

* [Babylon.js](https://cdn.babylonjs.com/babylon.max.js) - 3d library (right-click and Save As to a folder)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/) - Firefox is the recommended Web browser. Any browser that supports WebGL will work, but the ArcadeSimplex codebase has been tested extensively with Firefox.
* [Visual Studio Code](https://code.visualstudio.com/download) - Visual Studio Code is the recommended text editor. Any editor will work (you can even use Notepad!), but Visual Studio Code is a lightweight editor with very nice syntax highlighting and the ability to debug ArcadeSimplex using Firefox.
* [Git](https://git-scm.com/downloads) - A version control manager. This app isn't technically required but it makes check out the different codebase branches very easy, as well as help you manage your game development as you add features and your game becomes more complex.
