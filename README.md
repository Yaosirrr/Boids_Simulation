# Boids_Simulation

## Description

This is a course project for ECE6563 at Georgia Tech, most of the codes are copied from https://github.com/meznak/boids_py by meznak.

## How to run the simulation
1. Make sure you installed python and pygame. To install pygame, simply run `pip install pygame`.
2. Clone the repo or download all the files in this repo, put them into the same folder
3. Run the following command `python main.py`

## Parameters
When run `python main.py`, you can also personalized your arguments. This program supports -
1. The number of 'birds', the format is --number <number_you_want>
2. The fontsize of the pygame window, the format is --geometry <500x500>
For example:
`python main.py --geometry 500x500 --number 50`

## Keys Support
During this program, you can also press the following keys to perform different behaviors.
1. `q` - quit the simulation
2. `UP` - add more birds
3. `DOWN` - reduce the number of birds
4. `1` - divide the max_force by 2
5. `2` - double the max_force
6. `3` - reduce the perception by 20%, perception controls the range of the neighbors
7. `4` - add the perception by 20%
8. `5` - reduce the crowd by 20%, crow controls the collision avoidcance distance between two birds
9. `6` - add the crowd by 20%
10. `d` - debug mode, show the velocity, acceleration, position vector
11. `r` - reset the game
