Password Generator Using Reinforcement Learning

The project has two parts, firstly, a random forest classifier for classifying the strengths of passwords and secondly, a reinforcement learning model using Q learning algorithm to generate strong passwords. 

State Representation: The agent's state is represented by the current composition of the password being generated (e.g., length, number of uppercase letters, lowercase letters, special characters, and digits). This representation allows the agent to capture relevant patterns in password strength.

Action Space: The agent can take several actions, such as adding an uppercase letter, a lowercase letter, a special character, or a digit, based on its current state and learned policy.

Reward System: The agent receives rewards based on the strength of the generated passwords. A strong password results in a positive reward, while a weak password leads to a negative reward.

Experience Replay: To improve learning efficiency, the agent stores its experiences and samples them randomly to train the model in batches.

Exploration vs Exploitation: Initially, the agent explores different actions to learn about the environment. As it gains experience, it shifts towards exploiting the best-known actions to generate strong passwords.

The agent's performance is evaluated based on the accuracy of generated passwords classified into different strength categories.
