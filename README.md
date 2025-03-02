# CS-370-Portfolio


### Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?  
The implementation of deep Q-learning for a treasure hunt game is the main goal of this project.  The idea is to create an intelligent agent—a pirate—that can navigate a maze and find the treasure before an opponent can.

I was given two Python classes, **`TreasureMaze.py`** and **`GameExperience.py`**. The environment maze is defined by **`TreasureMaze.py`** and is shown as an 8x8 matrix. To enable the agent to learn from prior encounters, **`GameExperience.py`** stores game episodes. Additionally, the Jupyter Notebook provided a structured framework, including utility functions for visualizing the maze and setting up the game. My main contribution was to finish the deep Q-learning implementation by filling in the provided skeleton code.  This included training the pirate agent using the Q-learning method and adjusting hyperparameters like the exploration rate, learning rate, and discount factor. To ensure the agent can strike a balance between **exploitation** (applying learned methods) and **exploration** (finding new paths), the trained model is tested to see how well it navigates the maze. Through this work, I gained a deeper understanding of reinforcement learning, neural network training, and the practical application of AI in game environments.  

---

### Connect your learning from throughout this course to the larger field of computer science:  
This project connects to broader computer science principles, particularly artificial intelligence and reinforcement learning. The course covered essential AI methodologies that were instrumental in developing the pirate's decision-making model. In the larger field of computer science, these concepts extend beyond games and can be applied to robotics, autonomous vehicles, and recommendation systems. The ability to train intelligent agents to navigate complex environments is a game-changer in multiple industries.  

Moreover, this project reinforced the importance of data-driven decision-making, where an agent iteratively improves through trial and error—just as AI is used in modern problem-solving, from fraud detection to medical diagnosis.  

---

### What do computer scientists do and why does it matter?  
Computer scientists apply problem-solving methodologies to develop efficient and scalable solutions. They work across various fields, including software engineering, AI, cybersecurity, and data science. Their work matters because nearly every aspect of modern life relies on computing, from healthcare and finance to entertainment and transportation. Whether optimizing search algorithms, designing secure encryption methods, or developing AI-driven applications, computer scientists drive technological advancements that improve efficiency, security, and accessibility in digital systems. In this project, we saw how reinforcement learning can enhance decision-making in uncertain environments, a skill that has direct implications in fields like robotics and logistics.  

---

### How do I approach a problem as a computer scientist?  
The key to solving problems in computer science is **structured thinking**. Prior to developing any code, I make sure to clearly define the problem's scope and restrictions. Creating an AI agent that could effectively navigate a maze was the challenge in this instance. The next step is to break the problem down further into smaller manageable components. Examine these many components of the system, and in this project these include the training process (deep Q-learning), decision-making (reinforcement learning), and environment representation (the maze). Given these components, the next step would be selecting the right algorithm. Here, reinforcement learning was the appropriate algorithm because it allows the agent to improve over time. After finishing the initial implementation, I then attempt to improve performance, and tweak hyperparameters to further optimize the model. Lastly, I examine performance metrics, test the solution in various scenarios, and make necessary iterations as needed.  

---

### What are my ethical responsibilities to the end user and the organization?  
Ethical considerations are vital in AI and software development. My responsibilities include:  

- **Transparency & Fairness** – AI models should be free from biases that could lead to unfair decision-making.  
- **Data Privacy** – If real-world data were involved, protecting user information would be crucial. While this project used a simulated environment, in actual AI applications, responsible data handling is a major priority.  
- **User Experience & Safety** – The AI should enhance the user experience rather than create frustration or confusion. This is especially important in high-stakes applications like self-driving cars or medical AI.  
