## PPO

- PPO学习的是policy，即 $p(a_{t+1}|(s_t, a_t))$;
- 每一次actor与环境互动得到的数据可以用于更新policy好几个epoch；
- 使用importance sampling方法弥补训练数据的actor与当前actor行为之间的差异；
- 属于on-policy算法；
- $\epsilon$探索；

## DQN

- DQN学习的是Q-function，即 $Q(s_t, a_t)$ ,表示在$s_t$采取 $a_t$ 时，接下来直到游戏结束预期会获得的reward；
- 采样数据时总是选取当前state下可以获得最大Q值的action到训练数据中；
- target net和policy net结构一样，是policy net的滞后版本；
- $\epsilon$探索；
- 经验回放；