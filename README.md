# vizdoom-ai
Group work for 02456 Deep learning course at Technical University of Denmark.

As Deep Reinforcement Networks have progressed fast, autonomous agents have started to outperform humans in simple games such as the ones made by Atari in the 80s. In our coursework we combined monochrome pixel data with game feature information to train a Deep Q Network to play Doom in its Artificial Intelligence Research Platform: ViZDoom. By training the policy in separate learning phases, first with a navigation reward and then with a shooting reward, the policy succeeded to show significant improvement in only 2x200 epoch leaning. The policy developed a very specific strategy and scored higher than average built-in bots. The strategy was especially successful in the ViZDoom death match scenario.

To use the DNN build ViZDoom. Then clone the repository https://github.com/martinsimon88/vizdoom-ai into the ViZDoom folder and copy visdoom.so from examples/python into vizdoom-ai/python/. [ViZDoom][https://github.com/njustesen]
