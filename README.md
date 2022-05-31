# Effectiveness of Pitch Sequencing

## Abstract (1 paragraph)

It's the bottom of the 9th, tied game, bases loaded, and 2 outs. The pitcher needs one strike to secure the win. What do you throw? A fastball? A curve? The answer to that question might lie in a different question: What was the previous pitch?
If it was a fastball, the common answer would be a slider. This idea of combining certain pitches is called pitch sequencing, and currently, this part of pitching strategy is more art than science. However, by modeling data from the MLB, variables like spin axis and velocity can be compared to observe whether certain combinations of pitches are effective. From this it may be possible to determine a definitive answer to the original question, what do you throw?

## Context (2 paragraphs)

- What is the problem?
Baseball is a game uniquely defined by the defense's control of the ball. Defense in Baseball has two principal components - Pitching and Fielding. Fielding only becomes necessary when the offense successfully makes contact with the ball. This puts pitching at the forefront of defense and makes pitching strategy a key strategy to winning. Pitching strategy is defined by commonly accepted strategies that center around keeping the batter guessing. This is generally achieved by setting up a combination of contrasting pitches that throws off the expectations of the batter. More formally, this is called pitch sequencing. The question of "what pitch should I throw?" is a question of pitch sequencing - and this is the question we seek to answer.

- Why is it important to solve?
Due to the nature of pitching being the first line of defense in baseball, increasing the effectiveness of pitching results in a direct increase in the chances for game success. A pitcher generally has two main concerns when confronting the batter: missed bats and reducing hard contact. The first is about throwing pitches that the batter is likely to miss on an attempted swing. The second is about reducing the offensive potential when a batter makes contact with the ball. Pitch sequencing can address both of these cases by providing which pitch set ups are least likely to result in hard contact and most likely to result in a missed swing.
Additionally, this approach would bring another element of data driven strategy to baseball. Currently, most of pitching strategy is driven by intuition and experience, with pitchers relying on the read of the situation and the batter. With a data driven strategy, these intuitions can be used to inform the base layer pitch suggestion of the model, increasing its overall effectiveness.

## Proposal (3 paragraphs)

- What is the specific question are you trying to answer?
Does sequencing affect pitching outcomes? In other words, are there certain combinations of pitches that lead to better or worse outcomes? Baseball revolves around the central contest between the pitcher and the batter. The success of the pitcher lies in throwing a pitch that the batter either (1) unsuccessfully swings at, or (2) incorrectly judges will be not be a strike. Being able to do so requires maximizing the uncertainty of the batter. This uncertainty is affected by many factors, one of which may be the sequence of previous pitches.

- How will you answer it?
This question will be answered by utilizing pitching data recorded by the MLB. Each observation has several physical qualities recorded of the ball and its trajectory, allowing for a granular view of each pitch and its comparison to previous pitches. Looking at quantities such as the spin axis, velocity of the ball, vertical and lateral movement, etc. we can observe if there is any difference in outcome for sets of pitches with particular sequences along these variables.


- What do you expect/hope to find?
We hope to see consistent effects of a two pitch combination, where pitch one with particular qualities tends to increase the effectiveness of pitch two with its own distinct qualities. The converse would also be enlightening to unconver, where one pitch works worse when setting up another. A third possible finding is that pitch sequencing is not impactful. This in itself would also be significant because it would mean there are no standard pitch combinations or common contrasts that work well together. In this case, the burden of pitching strategy would depend on the pitcher's ability to read the situation and the batter.

## Conclusion (2-3 paragraphs)

- Summarize the problem and your solution.
Many games of baseball have been decided by crucial moments in the contest between pitcher and batter. The effectiveness of pitching and pitching strategy are laid bare in these moments, with some games being lost because of poor decisions. These decisions may have been avoided given a better foundation on which pitch combinations are more effective. By determining whether two sequential pitches with certain contrasting pitch qualities are more or less successful, we are able to definitively provide a base line pitching strategy for more effective pitch sequencing.

- If applicable, describe how your solution could be important beyond your specific context--i.e. can it be generalized?
One possible extension of this study would be looking at how people react to changes in visual stumulus. Because the median pitch sits around 90mph traveling a distance of roughly 60ft, this may provide some insight into how much conscious thought can go into influencing reactions at split second timing.

- Discuss limitations and potential future directions to take the project.
A major limitation to the project is the potential for feature bloat. Without considering too much more about each game of baseball in which the pitch is taking place, there are already a lot of variables. And these describe simply the physical attributes of the pitch.
However, the flip side of this would be to expand the analysis to include more consideration of the game as a whole and its effect on the pitch. The obstacle for this is finding a way to incorporate these other variables without losing the ability to be a coachable strategy.
