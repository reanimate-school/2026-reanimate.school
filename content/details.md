+++
title = "Details"
date = "2026-04-02"
author = "Yann"
+++

# A Medium for Us All: Humanities and Engineering Collaborations in Retro Game Studies
## Aleksander Franiczek

This presentation discusses the value of interdisciplinary methods for studying retro games as both technical and artistic objects. While all video games are determined by the technology used for their development, the study of retro games in particular demands consideration of the creative ways that developers (and players) work with (and around) hardware limitations. To explore this idea, the talk will consider the insightful potential of mixed-methods retro game analysis that combines quantitative data from computer science with qualitative approaches from the humanities. Example projects include tracing the evolution of a retro game series and comparing official (i.e., port, remaster) and unofficial (i.e., modded, hacked) versions of a retro game. If game development requires interdisciplinary collaboration, then why shouldn’t game scholarship follow suit?

# Colour & Constraint; Designing Retro Game Palettes
## Femke Kocken

This presentation explores how technical limitations shaped the visual language of retro games through the use of colour palettes. Beginning with a short introduction to colour theory and visual perception, the talk examines how early hardware restrictions forced developers and pixel artists to make highly intentional colour choices. We will look at how palette limitations influenced aspects such as readability, atmosphere, contrast, and visual identity. The session concludes with a practical guide for designing colour palettes for games in AMOS Basic, which can be directly applied to the game jam. 

# Supercharge your C64 with C64 OS
## Gregory Nacu

In this presentation, Gregory will discuss the philosophy of C64 OS as well as technical choices and details about its implementation, with a live demo to illustrate his points.


# Renovating the Dungeon of Doom
## Martin Robillard

Rogue is a dungeon exploration computer game originally developed for Unix systems in the 1980s. It achieved widespread popularity and inspired follow-up "roguelike" turn-based games. In a dusty corner of the Internet, I found a Java port of the game, likely from the late 1990s. From the perspective of modern object-oriented design, this code base is fantastically convoluted: it incorporates bit-level memory optimisations carried over from programming on a VAX-11 with arbitrary use of object-oriented features. As this legacy code base is an eloquent argument for the value of object-oriented design principles, I undertook a renovation of the code base. This renovation consists of a Git repository of the game in various stages of (dis)repair. In this talk, I will explore the true monsters lurking in "The Dungeon of Doom" and how they can be leveraged as an entertaining way to learn software design in Java.

# Historic Software Engineering: Insights from Deluxe Paint for the Amiga
## Yann-Gaël Guéhéneuc

This presentation discusses Deluxe Paint, a significant graphics program released in 1985 for the Amiga platform. Developed at a time when hardware constraints were severe, Deluxe Paint (DPaint) was written in C and designed to run on machines with only 256 KB of total memory, divided into video and CPU RAM, and a Motorola 68000 CPU at 7.09 MHz (PAL) or 7.16 MHz (NTSC).

With Giuseppe Destefani and Fabio Calefato, we analyse and study the 17,001 lines of source code of this historic program to understand the constraints that guided its architecture, design, and implementation by developers who worked without widespread access to formal programming patterns, reference books, or online resources.

Our analysis covers the overall development, compilation, and quality of DPaint. We also discuss the architectural styles, design practices, and implementation idioms present in its source code, as well as its code complexity. We identify antecedents to 11 of the 23 Gang of Four design patterns, all implemented through C constructs, nine years before the GoF catalogue was published, plus seven Amiga platform-specific architectural idioms with no GoF counterpart.

We also show how DPaint exploited the compiler and the Amiga hardware for efficiency, including direct graphics manipulation and optimised memory access. These findings highlight the resourceful methods used by its developers to maximise performance on such constrained systems.