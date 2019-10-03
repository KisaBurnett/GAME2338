# Game Testing Concepts

## Bungie's Approach to Testing Halo 3

The official Bungie video titled "Halo 3: The Testing" shows multiple parts of the testing process that was used to prepare Halo 3 for launch. The test team utilized many forms of both whitebox and blackbox testing to ensure the game met acceptable quality standards before it ever hit the shelves.

### Functional Testing
The test team performed these tests daily to verify the game's necessary functions were working. They made sure the level would load, characters spawned in correctly, and that movement and combat features performed as expected. This was initially performed whitebox, but was later also done blackbox by individuals who were brought in to test the game as well.

### Load Testing
This form of testing was used on the Xbox Live matchmaking features to verify performance and stress-handling capabilities to make sure the system would be able to handle over 100,000 users accessing the game's servers at the same time. The testers specifically used both **automated testing** and **manual testing** to effectively simulate and test this scenario. The automated testing was whitebox, as it was performed in-house by a dedicated test team. Some manual testing of the matchmaking features was done blackbox in the Beta period to check functionality between regions.

### Stress Testing
Whitebox testers intentionally sought out ways they could break the game with unexpected behavior, including looking for "holes" in the environment that would let them escape the world map. They also performed unconventional actions such as jumping repeatedly in one spot for several minutes, firing weapons at the walls, and many others to find out if it would cause the game to crash. All unexpected results were carefully documented to provide feedback for the developers.

### Unit testing
Everyone involved in building Halo 3 performed testing on their own individual pieces before they were placed in the game. Artists tested their environments to ensure they would render properly. Vehicle designers verified their creations looked and performed correctly when driven around the map. The sound and music designers tested their pieces to make sure everything sounded correct. This was all whitebox testing, as it was performed in-house, by the people working directly on the game.

### Integration Testing
Whitebox testers were tasked with making sure newer builds of the game which implemented new features still functioned as expected. They made sure existing features were unaffected, and that new features did what they were supposed to do. This allowed developers to verify they were working on stable builds as they continued to implement more units of code.

### System Testing
This testing was performed once all the features of the game had been implemented, to make sure it functioned correctly as a whole. This blackbox testing was performed by people brought in with no internal knowledge of the game. It was done after all of the features had been added to check the entire system.

### Usability Testing
This blackbox testing was performed by individuals brought in from outside the company. One participant at a time would play a small portion of the game, and a team would observe them to gauge their level of enjoyment, and if they struggled to learn how to play the game. This helped designers learn how to adjust the game to make it more user-friendly without compromising an acceptable level of challenge.

### Playtesting
Part of this process was blackbox, as it was done with outside testers. Multiple participants were brought in at a time to provide a broader perspective of how much fun the game was to players. It was also valuable since issues were more easily highlighted when more than one person at a time experienced frustrating issues impeding progress or enjoyment. Some playtesting was also done whitebox, by Bungie employees who wanted to make sure they also enjoyed the game.

### Balance Testing
Playtesting also provided feedback on the balance of the game from a blackbox user perspective. Designers used heat maps that showed where players had the most difficulty in levels to determine whether or not the challenges were fair. The maps included videos of gameplay to show what happened to different players at that spot. This exposed areas where potential issues existed, such as the enemies being too strong or the level giving those enemies an unfair advantage.

## Resources
[Official Bungie Video - Halo 3: The Testing Part 1](https://www.youtube.com/watch?v=H0sgH3maxlU)
[Official Bungie Video - Halo 3: The Testing Part 2](https://www.youtube.com/watch?v=ZMj_YjKmp98)
