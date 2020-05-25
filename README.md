python runner.py --num-bandits 10 --bandit-sampling-mean 0 --bandit-sampling-std-dev 1 --bandit-std-dev 5 --mode eps-greedy --num-trials 2000 --num-episodes 1000

python runner.py --num-bandits 10 --bandit-sampling-mean 0 --bandit-sampling-std-dev 1 --bandit-std-dev 1 --mode ucb --num-trials 2000 --num-episodes 1000 --ucb-degree-exploration 2

python runner.py --num-bandits 10 --bandit-sampling-mean 4 --bandit-sampling-std-dev 1 --bandit-std-dev 1 --mode gradient --num-trials 2000 --num-episodes 1000 --gradient-step-size 0.1


I have made this change in the dev branch


Adding more changes as requested

Change one devBranchSquashed

Change two - one more bogus commit

"Change made on master"