# LunarLander-DQNs

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/virtualms/LunarLander-DQNs/blob/main/LunarLander_DQNs.ipynb)

The aim of this project is to experiment some DQN variants on [LunarLander-v2](https://github.com/openai/gym/wiki/Leaderboard#lunarlander-v2) environment, offered by [gym.openai](https://gym.openai.com/). In particular, the variants that will be implemented and compared (refer also to the report of the project) are:
* [DQN](https://arxiv.org/abs/1312.5602)
* [DQN with target network (Fixed Q-Targets)](https://www.nature.com/articles/nature14236)
* [Double DQN (DDQN)](https://arxiv.org/abs/1509.06461)
* [Dueling DQN](https://arxiv.org/abs/1511.06581)
* [Dueling Double DQN (D3QN)](https://ieeexplore.ieee.org/document/8483478)

In all the reported versions, an experience replay was implemented.


## Results

The results of all the experiments done are reported below. 

You can download everything [here](https://drive.google.com/drive/folders/1uvXgLfkg-DP0Olj2bo8ToPh_u5lXKR3A?usp=sharing).

The mean reward over the last 100 episodes are reported. All models were trained for 500 episodes:
* **DQN**: 253.74
* **DQN + target network**: 254.50
* **DDQN**: 237.42
* **DDQN with soft update**: 144.97
* **Dueling DQN**: 238.49
* **D3QN**: 270.73


![rainbow_small](https://user-images.githubusercontent.com/50915778/138606906-eef56fb4-ed80-4167-8efe-9b307f742ffb.png)


Epoch 0:
https://user-images.githubusercontent.com/50915778/138607060-207d41bf-23fe-46fe-b707-0634f112df70.mp4

Epoch 500:
https://user-images.githubusercontent.com/50915778/138607066-d70a3ba8-4c46-442c-a104-9f09f6508eeb.mp4


