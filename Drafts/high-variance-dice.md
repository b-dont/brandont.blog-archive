# High-Variance Dice
How changing your dice can change your game experience.

> This was a post I wrote back in 2020 diving into the details of using high-variance dice in 5E systems. I'm reposting it here because I really enjoyed working on this one, and I think there's still some useful and fun information in it. Enjoy!

In April of last year the gaming-supplies company Wyrmwood Gaming launched a [Kickstarter](https://www.kickstarter.com/projects/wyrmwood/dice-by-wyrmwood/description) campaign for their new dice lineup. Alongside beautiful new sets of gemstone, resin, glass, and carved wooden dice, they announced a new numbering system that can now be requested with your dice set called “High-Variance”. In a [video](https://www.youtube.com/watch?v=z1oMnZW7Ry8&feature=emb_imp_woyt) released on their YouTube channel, Wyrmwood CEO Doug Costello explains their new system and the idea of maintaining the average roll value on a dice while increasing the probability of rolling values on the lower and higher ends of the number array.

### What Are High-Variance Dice?
I’m only going to cover the functionality and math behind these types of dice briefly in this post; I’m definitely not a mathematician or even well versed in these concepts. On the surface however, they are easy to understand and Wyrmwood does a great job explaining them in the video linked above and this short description from the Kickstarter page (also referenced above):

> “High Variance dice are dice that have been shifted to exaggerate extreme results, without sacrificing the overall average value of the rolls. For example, on a typical d6, you have the numbers 1, 2, 3, 4, 5, 6. The average roll is a 3.5. On a High Variance d6? 1, 1, 3, 4, 6, 6. The average roll is STILL a 3.5, however your chances of great success - or massive failure - have just doubled.”

So let’s talk about these dice. Today, I want to focus on their impacts on the game, how DMs and players can utilize them, how they may change the game, and how you can determine if these dice are right for you and your play-group.

Wyrmwood covers a few examples of how or when these dice might be used in the game, such as a specific narrative context where the outcome is either a success or a failure (which might as well be a coin flip). Another being the dice mirror the nature of a player character or non-player character’s personality; maybe their chaotic nature tends to favor or strive towards the extreme with their actions. Or maybe there’s a mechanical context that overlaps the narrative, such as an environment that impacts the players and their abilities, which I find the most interesting.

### How Do They Work?
So let’s start by briefly explaining how these dice work looking at the d20. I’ve written a short program in Python3 that illustrates the probability difference between a standard d20 that has the number array of 1-20, representing each value once, and the high variance d20. You can compare the two as well as each other dice type in the image below from Wyrmwood’s Kickstarter page.

![High-Variance Dice Compairison](https://brandont.blog/_images/header-image-dice.jpg)
_Source: [Wyrmwood Gaming](https://www.kickstarter.com/projects/wyrmwood/dice-by-wyrmwood/description)_
