# 🇦 🇻 🇱 🇪 🇦 🇷 🇳 🤖

# Advantage (A) and State-Value (V) functions learning

This is an alternative method to Q-learning, where a state-action value function Q is no longer considered as it is, and instead, a sum of advantage value function A and a state value function V is used (which is basically Q = A + V). Some may think it is superfluous, but we will try experimenting first and see where it gets us.

Also, please note that the only similarity with the [work](https://arxiv.org/abs/1511.06581) is in representing Q as A + V. The update (learning) algorithm is different here.

***The code will be here soon!***

# gymnasium [MuJoCo]

## Ant-V4 
Trained for 3 000 000 timesteps

| AV ( Ant-V4) | SAC (Ant-V1) | TD3 (Ant-V1) |
| ------------ | ------------ | ------------ |
|     7200     |     6000     |     6000     |

https://github.com/rohey/avlearn/assets/30954206/e600b17a-6e01-418d-8015-78b0b143f756

## HalfCheetah-V4 
Trained for 3 000 000 timesteps

| AV (HalfCheetah-V4) | SAC (HalfCheetah-V1) | TD3 (HalfCheetah-V1) |
| ------------ | ------------ | ------------ |
|     17000     |     16000     |     12000     |

https://github.com/rohey/avlearn/assets/30954206/d3a24f85-fd8a-4ccf-ae2e-3bb3b290bf80

https://github.com/rohey/avlearn/assets/30954206/824f4dfd-7b63-4dc4-8b8e-7a4565f83c34

## Swimmer-V4
Trained for 300 000 timesteps

| AV (Swimmer-V4) | SAC (Swimmer-V0) | TD3 (Swimmer-V0) |
| ------------ | ------------ | ------------ |
|     270     |     40     |     40     |

https://github.com/rohey/avlearn/assets/30954206/c68a95c5-beee-4e7f-9610-9f495cb6ee57
