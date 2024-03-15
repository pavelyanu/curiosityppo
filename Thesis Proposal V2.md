## Title:

Enhancing PPO with Intrinsic Rewards: A Study in the NetHack Environment

## Guidelines

Proximal Policy Optimization (PPO), a reinforcement learning algorithm, has shown promise in environments requiring strategic long-term planning. However, its effectiveness in environments with sparse rewards and long-term dependencies remains less explored. NetHack's challenging and dynamic environment – characterized by its procedural generation, multitude of entities, sparse rewards, and long-term dependencies – makes it an ideal testbed for enhancing PPO's performance in such settings.

This thesis will investigate the potential of reward-augmenting techniques to significantly improve the learning and performance of PPO agents in complex environments with sparse extrinsic rewards. Specifically, we will concentrate on Never Give Up (NGU), Random Network Distillation (RND), and Intrinsic Curiosity Module (ICM), applying them within a challenging and procedurally generated game environment like NetHack.

## References

1. John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov. "Proximal Policy Optimization Algorithms." ArXiv, 2017. https://arxiv.org/abs/1707.06347

2. Eric Hambro, Sharada Mohanty, Dmitrii Babaev, et al. "Insights From the NeurIPS 2021 NetHack Challenge." Proceedings of the NeurIPS 2021 Competitions and Demonstrations Track, PMLR, 2022, pp. 41-52. https://proceedings.mlr.press/v176/hambro22a.html

3. Heinrich Küttler, Nantas Nardelli, Alexander Miller, Roberta Raileanu, Marco Selvatici, Edward Grefenstette, Tim Rocktäschel. "The NetHack Learning Environment." Advances in Neural Information Processing Systems, 2020, pp. 7671-7684. https://proceedings.neurips.cc/paper_files/paper/2020/file/569ff987c643b4bedf504efda8f786c2-Paper.pdf

4. Deepak Pathak, Pulkit Agrawal, Alexei A. Efros, Trevor Darrell. "Curiosity-Driven Exploration by Self-Supervised Prediction." 2017 IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2017, pp. 488-489. https://ieeexplore.ieee.org/document/8014804

5. Nikolay Savinov, Anton Raichuk, Raphaël Marinier, Damien Vincent, Marc Pollefeys, Timothy P. Lillicrap, Sylvain Gelly. "Episodic Curiosity through Reachability." ArXiv, 2018. https://arxiv.org/pdf/1810.02274v1.pdf

6. Yuri Burda, Harrison Edwards, Amos J. Storkey, Oleg Klimov. "Exploration by Random Network Distillation." ArXiv, 2018. https://arxiv.org/pdf/1810.12894.pdf

7. Adrien Badia, Pablo Sprechmann, Alex Vitvitskyi, Daniel Guo, Bilal Piot, Steven Kapturowski, Olivier Tieleman, Martin Arjovsky, Alexander Pritzel, Andrew Bolt, Charles Blundell. "Never Give Up: Learning Directed Exploration Strategies." ArXiv, 2020. https://arxiv.org/abs/2002.06038

8. Rein Houthooft, Xi Chen, Yan Duan, John Schulman, Filip De Turck, Pieter Abbeel. "VIME: Variational Information Maximizing Exploration." Advances in Neural Information Processing Systems, 2016. https://proceedings.neurips.cc/paper_files/paper/2016/file/abd815286ba1007abfbb8415b83ae2cf-Paper.pdf

