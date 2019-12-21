---
layout: post
title: "AutoDock Vina"
---


## AutoDock Vina: Tips and Tricks for faster processing

AutoDock Vina is a very popoular program to perform protein-ligand docking. A large number of GUIs and extensions have been created by many people to make it easier to use Vina, yet somehow I still always prefer the out-of-box version of vina as it is for providing full control over your experiments and allowing you to customize your process.

There are literally so many ways to run vina, there is even a paper titled **"1001 Ways to run AutoDock Vina for virtual screening"** [Jaghoori et al, 2016](https://link.springer.com/article/10.1007%2Fs10822-016-9900-9), though I don't know what is it about, what I am trying to say is Vina is a robust and very versatile program which can be accessed through multitude of ways, through programatic access; through front ends like Chimera, PyMol, PyRx and many more; and of course through native command lines like **Command Prompt** in Windows, **Shell** in Unix/Linux etc.

Command line acces provides an easy way to run Vina through very simple commands and can be automated in various ways.

One question I always get asked when I take these workshops is that how do we prepare large number of ligands in an automated way so one doesn't have to prepare them one by one manually.

## Docking multiple ligands with AutoDock Vina

Command line applications provide an easy way to control your commands with variety of facilities. One of the useful tools is **loops** - just like any other programming language. These loops can help us complete repetitive tasks in an efficiant manner. 
