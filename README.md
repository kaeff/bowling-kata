# bowling-kata

http://www.butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata
https://kata-log.rocks/bowling-game-kata


Write a class `Game` that has two methods

1. `void roll(int)` is called each time the player rolls a ball. The argument is the number of pins knocked down.
1. `int score()` returns the total score for that game.


## [Bowling Scoring Rules](https://www.rookieroad.com/bowling/scoring-rules/)

Scoring in bowling is calculated on a rolling basis and is based on the outcome of each frame. In bowling there are 10 frames. A frame is made up of two bowls, so the bowler gets to throw the ball down the lane at the pins twice per frame.

There are 10 pins set up at the back of the lane. If you knock all 10 pins on the first bowl it's called a strike. If you eventually knock all 10 pins on your second bowl it's called a spare. Finally, if you fail to knock down all 10 pins it's called an open frame.

The 10th Frame: The bowler gets an additional roll if a spare is earned and two additional rolls if a strike is earned on the 10th frame. The total number of pins knocked down are added to the running total.

Symbol||Meaning
------------ | -------------
X or x|Strike
/|Spare
-|No pins knocked down
5 4|1st roll versus 2nd roll

