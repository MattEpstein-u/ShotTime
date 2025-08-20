# ShotTime
Simulation and analysis of a basketball exercise

Often when I practice basketball, I will set out to make two free throws in a row before leaving the gym. It gives me a sense of accomplishment at the end of the workout, regardless of the quality the rest of the workout.

One day, I set out to shoot three-pointers until I made 4 three-pointers in a row, and then immediately 4 free throws in a row. I started the exercise and I had no idea what I signed up for but I was determined to follow through. It took me around 25 minutes to complete the drill. When I got back to my computer, I designed a python code to simulate the expiriment.

**Question: How long can I expect to be doing the exercise?**

There are some assumptions for the purpose of data analysis:
Three-point percentage is constant: 40%

Free throw percentage is constant: 80%

The time is takes to retrieve the ball (rebound) and shoot the next shot is constant: 10 seconds

Variables:
SEED = 42 # Random seed for data reproducibility
REBOUND_TIME = 10 # Time to get the rebound and take the next shot in seconds
THREE_PT_PCT = 0.4 # 3-pointer percentage constant
THREE_PT_GOAL = 4 # Number of consecutive 3's needed to move on to the next stage
FT_PCT = 0.8 # Free throw percentage constant
FT_GOAL = 4 # Number of consecutive free throws needed to move on to the next stage
N_TRIALS = 100000 # Number of trials to average the data
