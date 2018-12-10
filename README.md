# Video Game AB Testing

[Link to project report](https://nbviewer.jupyter.org/github/marty-vanhoof/Video_Game_AB_Testing/blob/master/cc_ab_tests.ipynb#dataset)

This project analyzes the results of an AB test on the game [Cookie Cats](https://www.facebook.com/cookiecatsgame/).  At different points in the game, the player will occasionally encounter gates that make them wait for a span of time or make an in-app purchase to progress.  The first gate was initially set at level 30, and an experiment was done in order to see whether moving the first gate from level 30 to level 40 had an impact on player retention.

The data show that moving the gate to level 40 decreases both the 1-day and 7-day retention rates and the decreases are statistically significant (p-value < 0.01).  Therefore, it's a bad idea to move the gate to level 40.

The data from the AB test comes from [DataCamp](https://www.datacamp.com/).