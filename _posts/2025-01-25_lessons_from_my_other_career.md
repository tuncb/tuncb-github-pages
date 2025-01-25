---
title: "Lessons learned from my other career"
date: 2025-01-25
---

These days I earn my bread from programming. I write code, read code, think code. But before this I used to be a civil engineer. But today we will talk about my other other career.

Let's talk about Texas no limit holdem.

Texas no limit holdem is a variation of poker, probably the most popular one.
You start we two cards, and try to make the best hand combining your two cards with three cards from the table.
Betting round starts with your two cards, on the flop round three more  cards are opened to the table and two more cards are added on the turn and the river.
Usually two person from the game starts with a bet without seeing their cards to initiate the action.
At every pot the last person standing or the one with the best hand wins.
The "no-limit" part comes from the fact that there is no lemit to how much you can bet, but of course you can only bet the money you have.

Of course the goal is to win other people's money.
But it is not this simple.

Let's do a simple simulation:

Player A has AA and Player B has KK.
They go all in preflop. And Player B wins on a board of KTT25.
Did Player B made the right decision?
Actually no, let's see get the luck out:
AA has a possibility of winning 80% and KK has 20% of winning chance.
This means that their expected values is
Player A = 100 * 0.8 = 80
and Player B = 100 * 20 = 20.

This is called the Skalansky box.

So is this how we calculate it?
No, actually poker is a game of ranges.

If in this situation both players are going all in with the same range of AA, KK and QQ then there is actually no money exchanged.
This calculation is called the Galfond box.

People have been creating strategies to get ahead of each other for many years now.
and we can summarize the definition of these strategies with two factors:
Looseness, a measure of how many situations people choose to play and their abrasiveness, how many situations they bet.


In the old days professionals choose a tight adn mid-aggressive style.
Then as the internet crowd came in the style in fashion changed to a more loose more aggressive style.
Then with the advancement of strategies best players chose loose hyper-aggressive and sometime hyper loose hyper aggressive style.

Then something happened:

The first public software that let you analyze different game trees were released.
And really smart people started figuring out points in the game theory optimal universe.
What we mean by game theory optimal is that they found strategies where no matter what the opponent did you would lose or win any many.
Of course this also lets you understand how your opponents diverge from the game theory as well.

People gained a knowledge advantage in this way. Which brings us to the real lessons.



Some other life lessons I learned:

* There is a game theory optimum way of playing in any game.
* The goal is to get the knowledge advantage.
* People are terrible at understanding game theory optimal solutions. Basketball is another example. It took decades to understand 3 is bigger than 2. Interestingly even after this fact, it took a decade or two for all teams to accept this fact.
* Even statistics might not be enough poker needed simulation.
* When people don't understand game theory optimal solutions they will conform to the current trend.
* If you are not basing your conclusions on optimum solutions you are probably following a trend.



