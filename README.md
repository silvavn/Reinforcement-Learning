#MDP/Reinforcement Learning Examples

My solution to Udacity/Berkeley/GeorgiaTech's Reinforcement Learning Assignments.

The first assignment consists of teaching an agent to walk in the environment using Markov Decision Processes (MDPs).

The second one consists of implementing the Q-Learning algorithm to make the agent walk in the same environment provided.

Lastly you should use the Q-Learning to teach an agent how to play Pacman.

The essential difference between Udacity/GeorgiaTech and Berkeley is that in the first there's a gamma factor and in the second gamma is called discount (which in fact is just the same thing.)

you can run this under Windows/Linux Environment by executing the following commands:

a) For MDP: python gridworld.py -a value -i 100 -k 10 

b) For Walking with Q-Learning: python gridworld.py -a q -k 100

c) If you want to teach the agent Manually with Q-Learning:  python gridworld.py -a q -k 10 -m

d) If you want your agent to play Pacman: python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid

e) if you want to know more: python gridworld.py -h OR python pacman.py -h
