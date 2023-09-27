# MNNCA
An implementation of the Multi-Neighborhood Neural Cellular Automata (MNNCA), enhancing traditional NCAs with increased expressiveness for complex pattern generation based on ideas for continuous CA by SLACKERMANZ.

## Abstract

Cellular Automata (CA) have long been foundational in simulating dynamical systems computationally. With recent innovations, this model class has been brought into the realm of deep learning by parameterizing the CA's update rule using an artificial neural network, termed Neural Cellular Automata (NCA). This allows NCAs to be trained via gradient descent, enabling them to evolve into specific shapes, generate textures, and mimic behaviors such as swarming. However, a limitation of traditional NCAs is their inability to exhibit sufficiently complex behaviors, restricting their potential in creative and modeling tasks. Our research explores enhancing the NCA framework by incorporating multiple neighborhoods and introducing structured noise for seed states. This approach is inspired by techniques that have historically amplified the expressiveness of classical continuous CA. All code is publicly available

## Examples

![Example GIF 3](Media/texture3.gif)

## References

1. John von Neumann. *Theory of Self-Reproducing Automata*. University of Illinois Press, Urbana, IL, 1966.
2. John Conway. The game of life. *Scientific American*, October 1970.
3. William Gilpin. Cellular automata as convolutional neural networks. *Physical Review E*, 100(3):032402, 2019.
4. Ettore Randazzo, Alexander Mordvintsev, and Craig Fouts. Growing steerable neural cellular automata. [arXiv preprint arXiv:2302.10197](https://arxiv.org/abs/2302.10197), 2023.
5. Alexander Mordvintsev, Eyvind Niklasson, and Ettore Randazzo. Texture generation with neural cellular automata. [arXiv preprint arXiv:2105.07299](https://arxiv.org/abs/2105.07299), 2021.
6. Daniele Grattarola, Lorenzo Livi, and Cesare Alippi. Learning graph cellular automata. *Advances in Neural Information Processing Systems*, 34:20983–20994, 2021.
7. SLACKERMANZ. [Understanding multiple neighborhood cellular automata](https://slackermanz.com/understanding-multiple-neighborhood-cellular-automata/), 2021.
8. Ken Perlin. Improving noise. In *Proceedings of the 29th annual conference on Computer graphics and interactive techniques*, pages 681–682, 2002.
9. Leon A Gatys, Alexander S Ecker, and Matthias Bethge. Image style transfer using convolutional neural networks. In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pages 2414–2423, 2016.
10. Eric Heitz, Kenneth Vanhoey, Thomas Chambon, and Laurent Belcour. A sliced wasserstein loss for neural texture synthesis. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, pages 9412–9420, 2021.
