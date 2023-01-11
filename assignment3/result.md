# Assignment 3 of CS269 2022 Fall

**NAME:** [Valen Xie]

**UID:** [605948363]


## Learning curves of TD3

(20 points are given to the code.)

### TD3 in Pendulum

(5 points)

![](td3_pendulum.png)


### TD3 in MetaDrive-Tut-Easy-v0

(5 points)

![](td3_meta.png)



## Learning curves of PPO

(15 points are given to the code.)

### PPO in CartPole

(2 points)

![](ppo_cartpole.png)

[TODO: Replace to your figure]



### PPO in MetaDrive-Tut-Easy-v0

(3 points)

![](ppo_meta.png)

[TODO: Replace to your figure]

I don't know why my PPO results seem really unstable I think my implementation is correct..

## Learning curves of GAIL

(15 points are given to the code.)

### GAIL in MetaDrive-Tut-Easy-v0

(5 points)

![](gail_meta.png)



## Generalization Experiment

In this section, you need to draw one figure
whose X-coordinate represents "the number of training scenes" and 
Y-coordinate represents "the episodic reward".

We expect two lines in the figure, showing the final training performance and 
the test performance varying with the number of training scenes. 

You can refer to the Figure 8 of the paper of  [MetaDrive paper](https://arxiv.org/pdf/2109.12674.pdf) 
to see the expected curves. [ProcGen paper](http://proceedings.mlr.press/v97/cobbe19a/cobbe19a.pdf) is also highly relevant.


Choosing one algorithm, you should train agents in `MetaDrive-Tut-[1,5,10,20,50,100]Env-v0` environments and test all agents in `MetaDrive-Tut-Test-v0`.

Please discuss the figure you get.


### The generalization curves

(20 points are given to the figure.)

![](gail_generalization.png)


[TODO]: Discuss the figure. Does it look normal? If not, why? Do you have any solution?

The figure looks normal.

![](ppo_generalization.png)

This figure does not look normal, I would increase the steps.


## Discussion

In this section, you are free to write down your ideas and discussion. 
You can also leave this section blank.
If you conduct extra experiments, please record them here.




