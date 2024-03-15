## Guidelines
Proximal Policy Optimization (PPO), a reinforcement learning algorithm, has shown promise in environments requiring strategic long-term planning. However, its effectiveness in complex, high-dimensional settings like the ASCII-rendered game NetHack is yet to be fully explored. NetHack's challenging and dynamic environment, characterized by its procedural generation and multitude of entities, makes it an ideal testbed for advanced AI strategies.

The aim of this thesis is to evaluate and enhance the efficacy of PPO in NetHack. The research will involve integrating and testing various extensions to PPO, such as recurrent neural networks for learning long-term dependencies, early stopping reward shaping and scaling as well as various other minor optimizations. These modifications are intended to adapt PPO to the intricate demands of NetHack's gameplay. Success will be measured using specific game-related metrics, including the number of ascensions and in-game scores. The outcome of this research will provide insights into the adaptability and scalability of PPO in challenging AI environments.

## References

1. Engstrom, L., Ilyas, A., Santurkar, S., Tsipras, D., Janoos, F., Rudolph, L., & Madry, A. (2020). Implementation matters in deep policy gradients: A case study on PPO and TRPO. International Conference on Learning Representations. Retrieved from [https://iclr.cc/virtual_2020/poster_r1etN1rtPB.html](https://iclr.cc/virtual_2020/poster_r1etN1rtPB.html)

2. Andrychowicz, M., Raichuk, A., Stańczyk, P., Orsini, M., Girgin, S., Marinier, R., Hussenot, L., Geist, M., Pietquin, O., Michalski, M., & Gelly, S. (2021). What matters in on-policy reinforcement learning? A large-scale empirical study. International Conference on Learning Representations. Retrieved from [https://openreview.net/forum?id=nIAxjsniDzg](https://openreview.net/forum?id=nIAxjsniDzg)

3. Dossa, R. F., Huang, S., Ontañón, S., & Matsubara, T. (2021). An empirical investigation of early stopping optimizations in proximal policy optimization. IEEE Access, 9, 117981-117992. [https://doi.org/10.1109/ACCESS.2021.3106662](https://doi.org/10.1109/ACCESS.2021.3106662)

4. Schulman, J., Wolski, F., Dhariwal, P., Radford, A., & Klimov, O. (2017). Proximal policy optimization algorithms. CoRR, abs/1707.06347. Retrieved from [https://arxiv.org/abs/1707.06347](https://arxiv.org/abs/1707.06347)

5. Campbell, J. & Verbrugge, C. (2017). Learning combat in NetHack. In Tenth Annual AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment (AIIDE 2017) (pp. 16–22). Retrieved from [https://ojs.aaai.org/index.php/AIIDE/article/view/12923](https://ojs.aaai.org/index.php/AIIDE/article/view/12923)

6. Küttler, H., Nardelli, N., Miller, A. H., Raileanu, R., Selvatici, M., Grefenstette, E., & Rocktäschel, T. (2020). The NetHack learning environment. In Proceedings of the Conference on Neural Information Processing Systems (NeurIPS). Retrieved from [https://proceedings.neurips.cc/paper/2020/hash/569ff987c643b4bedf504efda8f786c2-Abstract.html](https://proceedings.neurips.cc/paper/2020/hash/569ff987c643b4bedf504efda8f786c2-Abstract.html)

7. Dossa, R. F. J., Huang, S., Ontañón, S., & Matsubara, T. (2021). An empirical investigation of early stopping optimizations in proximal policy optimization. IEEE Access, 9, 117981-117992. [https://ieeexplore.ieee.org/document/9520424](https://ieeexplore.ieee.org/document/9520424)

8. Hambro, E., Mohanty, S., Babaev, D., Byeon, M., Chakraborty, D., Grefenstette, E., ... & Sypetkowski, M. (2022). Insights from the NeurIPS 2021 NetHack Challenge. In Proceedings of Machine Learning Research (pp. 1764-52). NeurIPS 2021 Competition and Demonstration Track. Retrieved from [https://proceedings.mlr.press/v176/hambro22a/hambro22a.pdf](https://proceedings.mlr.press/v176/hambro22a/hambro22a.pdf)