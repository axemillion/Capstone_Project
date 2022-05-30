# Effectiveness of Pitch Sequencing

## Abstract (1 paragraph)

It's the bottom of the 9th, tied game, bases loaded, and 2 outs. The pitcher needs one strike to secure the win. What do you throw? A fastball? A curve? The answer to that question might lie in a different question: What was the previous pitch?
If it was a fastball, the common answer would be a slider. This idea of combining certain pitches is called pitch sequencing, and currently, this part of pitching strategy is more art than science. However, by modeling data from the MLB, variables like spin axis and velocity can be compared to observe whether certain combinations of pitches are effective. From this it may be possible to determine a definitive answer to the original question, what do you throw?

## Context (2 paragraphs)

- What is the problem?
Pitching is a key strategy to winning in baseball. With an effective pitching strategy, the pitcher alone can win games. Pitching strategy is driven by the experience of coaches with many aspects like pitch sequencing being based on personal anecdote. There are commonly known strategies that

- Why is it important to solve?
Pitching strategy would become more effective and 

## Proposal (3 paragraphs)

- What is the specific question are you trying to answer?
Does sequencing affect pitching outcomes? In other words, are there certain combinations of pitches that lead to better or worse outcomes? Baseball revolves around the central contest between the pitcher and the batter. The success of the pitcher lies in throwing a pitch that the batter either (1) unsuccessfully swings at, or (2) incorrectly judges will be not be a strike. Being able to do so requires maximizing the uncertainty of the batter. This uncertainty is affected by many factors, one of which may be the sequence of previous pitches.

- How will you answer it?
This question will be answered by utilizing pitching data recorded by the MLB. Each observation has several physical qualities recorded of the ball and its trajectory, allowing for a granular view of each pitch and its comparison to previous pitches. Looking at quantities such as the spin axis, velocity of the ball, vertical and lateral movement, etc. I can observe if there is any difference in outcome for sets of pitches with particular sequences along these variables.


- What do you expect/hope to find?


## Conclusion (2-3 paragraphs)

- Summarize the problem and your solution.


- If applicable, describe how your solution could be important beyond your specific context--i.e. can it be generalized?


- Discuss limitations and potential future directions to take the project.
A major limitation to the project is the potential for feature bloat. Without considering too much more about each game of baseball in which the pitch is taking place, there are already a lot of variables. And these describe simply the physical attributes of the pitch.
However, the flip side of this would be to expand the analysis to include more consideration of the game as a whole and its effect on the pitch. The obstacle for this is finding a way to incorporate these other variables without losing the ability to be a coachable strategy.
