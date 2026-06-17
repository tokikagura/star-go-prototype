# 🌟 Hoshi Go (星囲碁)

> ⚠️ **Early Test Version**
> The Custom Strategy AI is still under active development and being improved. If you catch the CPU making desperate zombie-like invasions, or if you forge a cool counter-strategy, **feedback is welcome!**

## About

Hoshi Go is a Go-inspired strategy game focused on experimentation, accessibility, and new ways to enjoy board games. 

This project explores alternative ideas around Go-like gameplay, AI difficulty, and strategy design.

## Features

* Go-inspired board gameplay
* Multiple AI difficulty levels
* Expert difficulty designed for a serious challenge
* Visual move feedback (Last move indicator ring)
* Sound effects and gameplay feedback (Pure Web Audio synth)
* Automatic endgame scoring (No Komi area counting)
* Continuous improvements and experiments

## How to Play

* Place stones on the board.
* Surround opponent stones to capture them.
* Create territory and control the board.
* The player with the greater territory wins.

Hoshi Go introduces its own experimental adjustments while keeping the feeling of strategic board play.

> ⚠️ **Important Note on Scoring (The Cleanup Phase)**
> The prototype engine scans the board instantly upon consecutive passes and counts any stone physically remaining on the grid as "alive."
> 
> Therefore, before declaring a final **Pass**, players must explicitly capture and remove all of the opponent's "dead stones" from the board. Consider this tactical cleanup the true finale of the match!

## Version 1.5

Current version: **1.5 (Test Type)**

This version includes:
* Improved AI behavior (Anti-Zombie invasion safeguards)
* Better gameplay feedback & Last move indicator
* Synthetic sound effects (No external mp3 files required)
* Automatic score aggregator engine upon double pass
* Balance adjustments

## Installation

Download or play the latest version from itch.io.

## Copyright Notice

All rights reserved.

The original concepts, game design, rules, and related materials of Hoshi Go are protected by the creator.

You may study this project and experiment with it privately.

If you would like to modify, redistribute, or use Hoshi Go as a foundation for your own project, please contact:

Twitter: @_tokikagura

Permission and terms can be discussed individually.

Thank you for respecting the original work.

## Future

Hoshi Go will continue to evolve through small improvements and experiments.

The goal is not only to create a game, but also to explore new possibilities in strategy and game design.
