+++
title = "Game_Jam"
date = "2026-04-02"
author = "Yann"
+++

## SUMMARY

The goal of the game jam is to learn to design and implement a game within the constraints of computers of the 80s and 90s. We design and implement games in AMOS Basic, which is a Basic dialect dedicated to the Amiga computer series. It allows making use of all the hardware capabilities of the Amiga computers. However, to simplify development and bring AMOS Basic to the ["masses, not the classes"](https://en.wikipedia.org/wiki/Jack_Tramiel), we developed [CRVJA](https://crvja.reanimate.school/), an online editor and transpiler for a subset of [AMOS Basic](https://amospromanual.dev/), which we use to implement the games.

The game jam is highly collaborative, with participants from diverse backgrounds teaming up to create games. From design to implementation, everyone will be able to contribute and learn from others! Mentors from the humanities and engineering will drive the teams, while everyone will have a chance to touch every aspect of the games. A judge with a long experience in the game industry assessed the games of the last day and awarded "advances" to the different teams to flesh out their demos.



## REALISATIONS

Five highly-motivated teams worked for three days straight to design, draw, and implement their games, with the material and software support of the organisers.



### Escape From Reanimate
> Amr Abdalla, Alexandre Kotowicz, Ali Maher, and Gabriel Ullmann

Escape From ReAnimate is an adventure game written in CRVJA v1.1 that draws inspiration from classic point-and-click games from the 90s and early 2000s, such as Grim Fandango and Twinsen's Odyssey. In this game, you control an IT support employee who is working after hours, is forgotten by the summer school organisers, and ends up being left behind and getting locked inside the room ER1072. To leave, he needs to find the door's keycode by carefully analysing the clues on the rooms' posters, computers, and furniture. Escape From ReAnimate provides a short but fun experience for both ReAnimate participants and anyone interested in adventure, exploration, and puzzle games. It is appropriate for all ages and clearly displays text instructions to guide the player throughout their adventure.

See also the [game design document](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/GDD.pdf). The [source code](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Code/Game.asc) and the sprite banks ([1](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Code/AmosBank_Escape1.abk) and [2](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Code/AmosBank_Escape2.abk)) are available under the GPLv3+.

#### Screenshots

[![Screenshot1](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot1.thumb.png "Screenshot1")](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot1.png) [![Screenshot2](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot2.thumb.png "Screenshot2")](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot2.png) [![Screenshot3](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot3.thumb.png "Screenshot3")](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot3.png) [![Screenshot4](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot4.thumb.png "Screenshot4")](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot4.png)

#### Demo

[![Demo](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Screenshot1.thumb.png)](/GameJam/EscapeFromReanimate_Kotowicz_Maher_Abdalla_Ullmann/Gameplay.mp4)



### Galaxy Patrol
> Tahereh Bijani, Kevin C. Chua, Diego Tondorf, and Minette Zongo Meyo

A game for strategic thinkers and action-oriented players, with multi-parallax background, dedicated sprites for players and enemies, and of course power-ups and sounds! You pilot a spaceship with auto-shoot and must dodge enemy fire to survive. You collect power-ups to grow stronger while the difficulty increases over time. A fresh take on shooters in retro games with lightweight design and expandable content.

See also the [pitch presentation](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Pitch.pdf). The [source code](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/GalaxyPatrol_TCZB.asc) and the [sprite bank](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/gjs.abk) are available under the GPLv3+.

#### Screenshots

[![Screenshot1](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot1.thumb.png "Screenshot1")](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot1.png) [![Screenshot2](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot2.thumb.png "Screenshot2")](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot2.png) [![Screenshot3](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot3.thumb.png "Screenshot3")](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot3.png) [![Screenshot4](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot4.thumb.png "Screenshot4")](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot4.png)

#### Demo

[![Demo](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Screenshot1.thumb.png)](/GameJam/GalaxyPatrol_Tondorf_Chua_Zongo_Bijani/Gameplay.mp4)



### Park Bedlam
> Sikandar Ejaz, Aleksander Franiczek, Luca Scistri, and Al Muqshith Shifan

Created by the studio Birds of Prey, Park Bedlam is a turn-based, multiplayer tactical game inspired by the Fire Emblem series. Players must compete using strategic movement and unit positioning to optimise their chances for victory.

Reanimate Park used to be a place of harmony. A natural haven where birds and mammals with a tolerance for urban areas and the degenerate humans that occupy them lived in peace. However, in recent years, everything has changed due to a cruel invention: animal-proof trash cans. There haven't been enough food scraps to go around ever since. Critters now desperate for control over the park's landscape and the food waste it contains, such as Yann the Raccoon and Gael the Goose, have called for war. The park's mammals and birds have united with their lords for a battle of resources. Who will you support?

Two potential win conditions:
- Eliminate the other army’s leader (Yann or Gael)
- Eliminate all the other units aside from leader (forcing a surrender)

Four unit types between the two armies:
- Big: Geese and Raccoons (slowest)
- Medium: Ducks and cats
- Small: Pigeons and squirrels (fastest)
- Leaders are Big units, but their stats work differently

Each time two units face off there’s a six-sided dice roll that is modified +2 by unit weakness pairings.

See also the [pitch presentation](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Pitch.pdf). The [source code](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Code/park_bedlam_v20.asc) and the sprite banks ([1](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Banks/AleksBank.abk), [2](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Banks/Cat.abk), [3](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Banks/DuckSquirrel.abk), [4](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Banks/Pigeon.abk), and [5](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Banks/Raccoon.abk)) are available under the GPLv3+.

#### Screenshots

[![Screenshot1](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot1.thumb.png "Screenshot1")](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot1.png) [![Screenshot2](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot2.thumb.png "Screenshot2")](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot2.png) [![Screenshot3](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot3.thumb.png "Screenshot3")](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot3.png) [![Screenshot4](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot4.thumb.png "Screenshot4")](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot4.png)

#### Demo

[![Demo](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Screenshot1.thumb.png)](/GameJam/ParkBedlam_Shifan_Franiczek_Ejaz_Scistri/Gameplay.mp4)



### Welcome to the Backrooms
> Evan Bigot, Marco Uriel Lopez Garcia, Cristiano Politowski, and Henrique Serra

You and your friend are researchers wearing Hazmat suits. You were sent to map the endless and creepy dimension of the Backrooms. What started as a safe mission quickly turns into a nightmare when you find out you are not alone. Your mission is cancelled: now, your only goal is to survive.

To find the exit in each level, you must break the cracked walls. Your only tools for defence and digging are powerful bombs. But be careful: bombs hurt everyone. A bad throw will not only kill
the monsters, but it will also destroy your suits and end your lives.

You will go down through 12 levels of pure tension, each one deeper and more dangerous. Can you work together, survive the entities, and find your way back to reality?

See also the [game design document](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/GDD.pdf) and the [pitch presentation](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Pitch.pdf). The [source code](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Welcome_to_the_Backrooms.asc) and the [sprite bank](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Sprite.abk) are available under the GPLv3+.

#### Screenshots

[![Screenshot1](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot1.thumb.png "Screenshot1")](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot1.png) [![Screenshot2](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot2.thumb.png "Screenshot2")](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot2.png) [![Screenshot3](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot3.thumb.png "Screenshot3")](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot3.png) [![Screenshot4](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot4.thumb.png "Screenshot4")](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot4.png)

#### Demo

[![Demo](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Screenshot1.thumb.png)](/GameJam/Welcome_to_the_Backrooms_Politowski_Bigot_Serra_Lopez/Gameplay.mp4)



### World of Iris
> Yann-Gaël Guéhéneuc, Vinicius Mioto, Fabio Petrillo, and Peter Yefi

Iris, goddess of colours, will help you colour the world that has been turned grey by the evil Erebus. She will put paint pots in various places that you must catch before Erebus destroy them. You will use them to give back colours to the world! The game will help children understand colours, colour theory, and can be played infinitely with different backgrounds at each level.

See also the [pitch presentation](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Pitch.pdf). The [source code](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/WoI.asc) and the [sprite bank](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/WoI.abk) are available under the GPLv3+.

#### Screenshots

[![Screenshot1](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot1.thumb.png "Screenshot1")](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot1.png) [![Screenshot2](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot2.thumb.png "Screenshot2")](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot2.png) [![Screenshot3](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot3.thumb.png "Screenshot3")](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot3.png) [![Screenshot4](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot4.thumb.png "Screenshot4")](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot4.png)

#### Demo

[![Demo](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Screenshot1.thumb.png)](/GameJam/WorldOfIris_Mioto_Petrillo_Yefi_Guéhéneuc/Gameplay.mp4)



## EVALUATIONS

We had the honour to have [Chris Gibbs](https://www.linkedin.com/in/christopher-gibbs-50458223/) as judge of the game jam. Chris, upon graduating with a degree in Software Engineering in 1988, co-founded the UK games development studio, Attention To Detail and was its managing director through until 2003. ATD designed and developed video games for publishers worldwide, across all genres but notably racing, sports and action. From 2003 to 2012, Chris was Executive Producer and Studio Manager for Electronic Arts, specialising in Mobile Game Development and pioneering the move to touchscreens and games-as-a service. From 2014 to 2019 Chris designed, developed, and launched his own mobile game, Smart Numbers, which Apple made Game of the Week in over 50 countries.

The [evaluation criteria](/Presentations/260609a - Game Jam.pdf) set by Chris were in no particular order:

- Competitive advantage
- Intended audience
- Core gameplay
- Monetisation
- Realisation
- Design

Chris gave a [thorough and thoughtful evaluation](/GameJam/Evaluations.mp4) of each game and awarded some (Monopoly) "advances" to each one of them to flesh out their demos. 

- First place ex-aequo: Escape From Reanimate, $250,000
- First place ex-aequo: Park Bedlam, $250,000
- Second place: Welcome to the Backrooms, $200,000
- Third ex-aequo place: Galaxy Patrol, $100,000
- Third ex-aequo place: World of Iris, $100,000

C-O-N-G-R-A-T-U-L-A-T-I-O-N-S!
