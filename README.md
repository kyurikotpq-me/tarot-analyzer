# Tarot: Historical Analyzer
- [Tarot: Historical Analyzer](#tarot-historical-analyzer)
  - [Introduction](#introduction)
  - [The Data](#the-data)
  - [Your Task](#your-task)
    - [1. Comparison among Minor Arcana Suits](#1-comparison-among-minor-arcana-suits)
    - [2. Major VS Minor Arcana Comparision](#2-major-vs-minor-arcana-comparision)
    - [3. Upright VS Reversed Cards](#3-upright-vs-reversed-cards)
    - [Extra Task If You're Game](#extra-task-if-youre-game)
  - [Using this repository](#using-this-repository)
  - [Livestream Replay](#livestream-replay)
  - [Guides](#guides)
  - [Acknowledgements](#acknowledgements)

## Introduction
Tarot is an intuitive practice involving a deck of cards. Each deck comprises of 78 cards that each describes a theme in life (frustration, fear, letting go, etc.)

In a tarot reading, one or more questions are posed to the deck. Single or multiple cards are drawn and interpreted to form an answer to those questions. When multiple readings are done consistently over time, the cards drawn often reflect the energy and/or events of the question poser's life. The significance of the predominance of each card type are as follows:

| Card Type                | Meaning |
| ------------------------ | ------- |
| Upright                  | When many cards are upright, all your energies are expressing freely and powerfully. The overall situation is well developed, and your purpose is clear. |
| Reversed                 | When many cards are reversed, your energies are low, and the situation is not clearly defined. You may lack direction or feel blocked, discouraged and restricted. You could be in a topsy-turvy state where change is likely. Since energies are not well developed, they are free to go in new directions. |
| Major Arcana             | You are experiencing life-changing events that will have long-term effects. There are important lessons that you must pay attention to in order to progress further in your spiritual and personal quest.   |
| Minor Arcana             | You are dealing with day-to-day issues which will not necessarily have a lasting influence on your life. These issues are passing through, presenting you with an opportunity to learn from these experiences. Look to any Major Arcana cards in the Tarot reading to identify and understand these lessons and how they may impact your life in the long-term. |
| Minor Arcana - Cups      | You are seeking solutions to what are primarily emotional conflicts, personal interactions, love matters, feelings and creativity. |
| Minor Arcana - Pentacles | You are seeking solutions to what are primarily material conflicts, financial matters and concerns with career and work. |
| Minor Arcana - Swords    | You are seeking solutions to what are primarily mental struggles, conflict and arguments, and decisions that must be made. Also, there could be many arguments or even violence at present. While Swords can carry with them many negative or very strong, forceful messages, Swords serve also as a warning to be more cautious of what is occurring around you. |
| Minor Arcana - Wands     | You can be sure that you are seeking solutions to issues that are based mainly in the realm of thought, or that are in the first stages of development. You may also be seeking greater purpose and meaning in your life and will want to understand more about what motivates and energizes you. |

## The Data
The client has recorded his tarot reading for each day in its own file. These files can be found in the [sample-data](sample-data/) folder.

Each card is recorded using a coding system:
- Major Arcana cards have a `m-` prefix. So, The Fool would be `m-fool`
- Minor Arcana cards have the format `<number>-<suit>`.
  - `<number>` runs from 1 (Ace) through k (King) with Knight using the letter `n`
  - `<suit>` takes after the suit's first letter - Cups is `c`, Swords is `s`, and so on
  - So the Knight of Wands would be `n-w` while the Ace of Wands would be `1-w`
- Reversed cards have a `-r` suffix, regardless of Major or Minor Arcana. So, The Magician Reversed would be `m-magician-r`
- Every letter is in lowercase :D

## Your Task
You are tasked to program a script that will create **three (3)** visuals as follows:

### 1. Comparison among Minor Arcana Suits
There are four (4) Minor Arcana suits - Cups, Pentacles, Swords, Wands. Compare the number of cards drawn for each suit in a simple bar graph.

### 2. Major VS Minor Arcana Comparision
Compare the number of cards drawn for major and minor arcana in a pie chart.

### 3. Upright VS Reversed Cards
Compare the number of cards drawn that were upright and those that were reversed in a donut chart.

> FYI, I made the chart types different so that you can practice looking up the documentation for each type. Sorry if it's not the correct type to use >_<

### Extra Task If You're Game
For each of the above comparisons, present the meaning for the "prevailing" type. For instance, for Task 3), if there are more Upright cards than Reversed cards, display a description on what having more Upright cards mean. These descriptions are listed in the table above.

Save all your work in a single Jupyter notebook, `analyzer.ipynb`, in the `scripts` folder.

## Using this repository
The `main` branch is your starting point. When you're done, check out the `answer` branch for my solution.

> Note that like Maths, there are a lot of ways to achieve the same outcome in programming, so don't fret if your work is very different (it should be!)

If you want an easier option, you can check out `main-easy`. Only the initial step is easy; the desired outcomes are the same.

## Livestream Replay
The livestream replay can be found [here](https://youtube.com).

## Guides
If you're truly starting from scratch, here are the steps you need to follow:
1. Install Python 3.8+ (if not using MacOS)
2. Install a code editor software on your computer. I prefer using Visual Studio Code ("VS Code") - it's free works right out of the box
3. If you're using VS Code, I have recommended extensions to help you work faster :D

If you don't wanna watch the replay, I've summarized the process I have for approaching programming problems [here](wiki/programming-process.md). I've also summarized [best practices](wiki/best-practices.md) that have helped me debug more quickly.

Both lists are not exhaustive, so feel free to experiment and create your own list :D

## Acknowledgements
The card meanings are obtained from [Biddy Tarot](https://biddytarot.com).
