# 440-acrobot-project
A repo for Merrick Summers and Jonathan Wu to work on their ENME440 project.
The project is training a reinforcement learning agent to swing the end of a double pendulum up past a certain line by controlling the torque on a bottom pendulum. The success criteria is a mean reward greater than -100 over 100 consecutive episodes.
This is the "Acrobot" controls problem.

References: (not really comprehensive)
- Gymnasium docs on Acrobot: https://gymnasium.farama.org/environments/classic_control/acrobot/
- Acrobot leaderboard: https://github.com/openai/gym/wiki/Leaderboard
- PyTorch DQN tutorial w/ Gymnasium: https://docs.pytorch.org/tutorials/intermediate/reinforcement_q_learning.html
- Actor-critic solution (this guy also has an interesting looking project that seeks to unpack all of the mathematical fundamentals of machine learning that are frequently mystified because of their implementations being far in the back-end of commonly used libraries): https://www.henrypan.com/blog/2019-12-03-acrobot/
- Q-table reference solution video: https://www.youtube.com/watch?v=Pf1lEv3b5s4
- Q-table reference solution repository: https://github.com/johnnycode8/gym_solutions/blob/main/acrobot_q.py
