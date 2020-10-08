# awesome-latent-control
A collection of resources regarding the interplay between control, causality, latent structure and self-supervision.

**NOTE:** Feel free to suggest additional resources via `Issues` or `Pull Requests`.

# Table of Contents

* **Latent space control**

	* [Learning from observations](#world-models)


## Latent space control

*  First Steps: Latent-Space Control with Semantic Constraints for Quadruped Locomotion: [IROS20](https://arxiv.org/pdf/2007.01520.pdf)
> Traditionally, trajectory optimisation for quadrupeds is solved using constrained optimisation. However, the robots feasible joint space and dynamics such as stability, torque limits, and contact forces, require complex often nondifferentiable constraints. This makes the optimisation intractable. A typical approach, therefore, is to use approximate, hand-derived dynamic models and arbitrarily reduce the kinematic range of the robot. Here, we propose a radically different approach to quadruped control. Using a generative model of the robot state we perform trajectory optimisation by directly optimising the position in a structured latent space, which captures a statistical model of the robots feasible joint-space

## Learning from observations

* Mastering Atari With Discrete World Models: [NeurIPS20](https://arxiv.org/pdf/2010.02193.pdf)

> Compared to model-free reinforcement learning that learn through trial and error, world models  facilitate generalization and can predict the outcomes of potential actions to enable planning In this paper, we introduce DreamerV2, the first reinforcement learning agent that achieves humanlevel performance on the Atari benchmark by learning behaviors purely within a separately trained world model

* Causal Discovery in Physical Systems from Videos: [NeurIPS20](https://arxiv.org/pdf/2010.02193.pdf)

> We consider the task of causal discovery from videos in an end-to-end fashion without supervision on the ground-truth graph structure. . In particular, our goal is to discover the structural dependencies among environmental and object variables: inferring the type and strength of interactions that have a causal effect on the behavior of the dynamical system. Our model consists of a perception module that extracts a semantically meaningful and temporally consistent keypoint representation from images, an inference module for determining the graph distribution induced by the detected keypoints, and a dynamics module that can predict the future by conditioning on the inferred graph. The main contributions of this work lie in the one-shot discovery of unseen causal mechanisms in new environments from partially observed visual data in a continuous state space.





