# AttentionLearnerLayer
a Layer that learns where to pay attention using reinforcement learning(PPO algorithm)


- **PPO**

With supervised learning, we can easily implement the cost function, run gradient descent on it, and be very confident that we’ll get excellent results with relatively little hyperparameter tuning. The route to success in reinforcement learning isn’t as obvious — the algorithms have many moving parts that are hard to debug, and they require substantial effort in tuning in order to get good results. PPO strikes a balance between ease of implementation, sample complexity, and ease of tuning, trying to compute an update at each step that minimizes the cost function while ensuring the deviation from the previous policy is relatively small.

![Loss function ](https://miro.medium.com/max/700/1*bzSagTz4kZxRLuXLviWlxA.jpeg)

by using above algorithm we try to teach a nueral net to create a input shape tensor that only contains numbers between zero and one. this tensor act like a filter that decide which parts of input are imprtant and which parts aren't.


to be continued ....
