* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/

# Hide-and-Seek
 Through multi-agent competition, the simple goal of hide-and-seek and standardized augmentative learning algorithms on a large scale, we find that agents create a self-supervised approach that catalyses multiple distinct rounds of emerging strategy, many of which require sophisticated use and coordination of the tool. We find clear evidence of six emerging stages in the agent's strategy in our environment, each of which creates new pressure on the opposing team to adapt; For example, Agents learn to build multi-purpose shelters using moving boxes which in turn lead to Agents discovering that they can overcome obstacles using ramps. We also provide evidence that multi-agent competition may better expand with increasing environmental complexity and lead to behavior focused on more human-relevant skills than self-supervised reinforcement learning methods such as intrinsic motivation. Finally, we propose transfer and tuning as a method to quantitatively assess target abilities, and compare hide-and-seek factors with both intrinsic motivation and random baselines on a set of domain-specific IQ tests.
 
 
 ![1](https://user-images.githubusercontent.com/35774039/119997298-423bf980-bfd8-11eb-9d6f-00bf31891de3.JPG)
![2](https://user-images.githubusercontent.com/35774039/119997327-48ca7100-bfd8-11eb-9a75-9dab325d7881.JPG)
Skill development arising from a subjective, multifactorial approach. With the hiding bonus signal (shown on the y-axis), customers go through 6 distinct stages of emergence. (A) Researchers (in red) learn to chase jewelers, and refugees learn to run rudely. (B) Sliders (in blue) learn to use basic tools, using the boxes and walls sometimes found to build forts. (C) Researchers learn to use the ramps to jump into a cavalry shelter. (D) Burrows quickly learn to move the ramps to the edge of the play area, away from where they will build their castle, and lock it in place. (e) The researchers learn that they can jump from locked ramps to unlocked chests and then navigate the chest to the hideouts of the hideout, which is possible because the environment allows agents to move with the chest regardless of whether they are on the ground or not. (F) The hideouts learn to lock all unused chests before building their fort. We plot the average on more than 3 independent training sessions with each individual seed indicated by a dotted line.


POLICY OPTIMIZATION
Agents are trained using self-play, which acts as a natural curriculum as agents always play opponents of an appropriate level.
Agent policies consist of two separate networks with different parameters - a policy network that produces an allocation of action and a critical network that predicts discounted future returns. Policies are improved using public advantage estimation, and training is conducted using a rapid (OpenAI, 2018), large-scale distribution of the RL framework. We use decentralized implementation and centralized training. At the time of execution, each agent gives his actions only his observations and his own memory state. At the time of optimization, we use an omniscient central value function for each agent, which can access the whole environment state without any persuasive information due to visibility.

![4](https://user-images.githubusercontent.com/35774039/119997434-68fa3000-bfd8-11eb-9074-6b085c133e46.JPG)

