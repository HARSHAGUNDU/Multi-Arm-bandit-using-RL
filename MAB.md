This project is regarding the implementation of multi arm bandit using Reinforcement Learning.
      
Bandit is a slot machine with a levers with different rewards each.When the player pull any particular lever, it gives rewards . But we don’t have the knowledge on which arm we should invest on so that we can fetch maximum rewards.

To invest wisely and optimize our investment , we are using Reinforcement Learning to gain maximum rewards.

Before going deep into the project, let us acknowledge what is Reinforcement Learning.Reinforcement learning is a branch of machine learning that explores how intelligent agents should behave in a particular scenario in order to maximize the concept of cumulative reward under uncertainity.

We are using the following Action-value methods in our project:  
1 . Epsilon Greedy approach  
2 . Upper Confidence bound (UCB)  

1 . Epsilon Greedy approach :It is the simplest way to alternate exploration and exploitation by maintaining balance    between them.
2 . Upper Confidence bound  :It is based on the principle of optimism in the face of uncertainty 

In this Multi-Arm Bandit implementation,we are dealing with exploration and exploitation which are the core ideas of Reinforcement Learning.

Exploitation :Exploits agent's current estimated value and chooses the Epsilon greedy approach to gain more rewards.
Exploration  Exploration is a long term benefit where the agent explores to gain its knowledge.

In our project , there are 3 main components :  
-> State    
-> Action    
-> Reward  

Average reward per No.of iterations!:  

![image-2.png](attachment:image-2.png)

1.Epsilon-Greedy using different exploration rates : 

From this plot we can see that exploration rate with 0.1 did better than the 0.3
![image-3.png](attachment:image-3.png)

2 . Upper Confidence bound  :   

from this plot we can see that UCB outperformed the Epsilon-Greedy
![image-4.png](attachment:image-4.png)


```python

```


```python

```


```python

```


```python

```
