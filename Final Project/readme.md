# RL-CNN Pong Game Agent

This repository contains a project that implements the concepts of deep reinforcement learning (RL) using convolutional neural networks (CNNs) for the game Pong. The project is based on the paper "Playing Atari with Deep Reinforcement Learning" (cited by 10,853) published in 2013. The goal of the project is to train an RL agent that can learn to play Pong by watching a video of the game and interacting with the environment.
## Getting Started

The project is implemented in Python and requires the following packages to be installed:

   - Pytorch
   - Numpy
   - Matplotlib
   - Gym

To run the project, simply execute the main.py file. The script will automatically train the agent and display the results in the form of a video.
Additional Resources

In addition to the "Playing Atari with Deep Reinforcement Learning" paper, the following resources were used in the implementation of this project:

   1. *Mnih, Volodymyr, Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou, Daan Wierstra Martin Riedmiller: "Playing Atari with Deep Reinforcement Learning", arXiv preprint arXiv:1312.5602, 2013.*
   2. *Mnih, Volodymyr, Koray Kavukcuoglu, David Silver, AndreiA Rusu, Joel Veness, MarcG Bellemare, Alex Graves, Martin Riedmiller, AndreasK Fidjeland, Georg Ostrovski: "Human-level control through deep reinforcement learning", Nature, 518(7540):529–533, 2015.*
   3. *Van Hasselt, Hado, Arthur Guez David Silver: "Deep Reinforcement Learning with Double Q-Learning", Proceedings of the AAAI Conference on Artificial Intelligence, 30, 2016.*
   4. *Wang, Ziyu, Tom Schaul, Matteo Hessel, Hado Hasselt, Marc Lanctot Nando Freitas: "Dueling Network Architectures for Deep Reinforcement Learning", International Conference on Machine Learning, 1995–2003. PMLR, 2016.*
    

A table listing these resources and their citation count is included at the end of this README.
## Functionalities

The code includes a number of functionalities such as the ability to:

   - Save and resume training
   - Change the frequency of target network updates
   - Use double DQN

## Acknowledgements

The author would like to express their gratitude to Prof. SaeedReza Kheradpisheh, Assistant Professor in the Mathematics and Computer Science Faculty of Shahid Beheshti University, for providing guidance and support throughout the Artificial Neural Network course and supervising the final project which is an implementation of the "Playing Atari with Deep Reinforcement Learning" article written by DeepMind team of Google. The author would also like to appreciate the efforts of the course's Teaching Assistants, Mr. Arsham Gholamzadeh and Mr. Alireza Javaheri, in defining assignments and the final project. A special thanks to Prof. Hossein Hajiabolhassan, Professor of Shahid Beheshti University, for introducing the author to the field of reinforcement learning and his valuable guidance as a supervisor of the author's master's thesis wich is related to the field of RL.

## Additional Materials

In addition to the PDF report, the Github page includes:

   - Videos of the agent playing the game during the learning process
   - Python code
   - Saved model
   - Text output of the code
   - results graph


Table of papers and citation count
|   |                         Title of paper                        | Cited by | Year |
|---|:-------------------------------------------------------------:|:--------:|:----:|
| 1 | Playing Atari with Deep Reinforcement Learning                |  10,853  | 2013 |
| 2 | Human-level control through deep reinforcement learning       |  22,480  | 2015 |
| 3 | Deep Reinforcement Learning with Double Q-Learning            |   6,220  | 2016 |
| 4 | Dueling Network Architectures for Deep Reinforcement Learning |   3,316  | 2016 |


