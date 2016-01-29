# gosu-mario
## Project for the speed sprint workshop [first presented at Toronto Ruby Hack Night, January 28, 2016]

This project, based on the gosu-examples project, has been selected to be a part of the speed-sprint workshop.
The speed-sprint project can be found here: https://github.com/k00ka/speed-sprint.

# User Stories
1. Add scoring + create a new level for testing and “contribution to greater good”

  Why collect rubies if they aren't worth anything? Users should get a score for collecting rubies. Design a new level, maybe something the dev team can use down the road.

  Team #1: Finished. The game's physics seem fine. We added the ```@score``` variable (currently line 201) within the Mario class to keep track of gems collected. ```Player.collect_gems``` has been edited to do the score calculation on each draw. A score display was added up top.

2. A level “exit” that opens when a level is complete and leads to a series of levels

  Our levels need a purpose. Create an 'exit' for the level that will open once some task has been accomplished. Obviously, once you exit the level, you should appear in a new one.

3. Add three lives + tiles that kill you + create a new level for testing

  The game needs more challenges. The player should have a number of lives and should be able to die. Also create some tiles (maybe fire, spikes, or rusty spoons?) that can kill the player. Add a new level where a player will face these new challenges.

4. Tiles that move

  Levels need more excitement. Create some moving tiles, so the levels have greater difficulty. Create a new level that features these moving tiles.

TEAM #2:

Exit sill needs to be added look for this code ```if @maps.gems.count == 0```
