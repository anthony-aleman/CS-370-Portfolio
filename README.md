# CS-370-Portfolio


### Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?  
This project focuses on implementing deep Q-learning for a treasure hunt game. The goal is to develop an intelligent agent—a pirate—that navigates through a maze to find the treasure before an opponent does.  

I was given two Python classes:  
- **`TreasureMaze.py`**: Defines the environment, which is represented as an 8x8 matrix.  
- **`GameExperience.py`**: Stores episodes of the game to allow the agent to learn from past experiences.  

Additionally, the Jupyter Notebook provided a structured framework, including utility functions for visualizing the maze and setting up the game.  

My main contribution was completing the deep Q-learning implementation by filling in the provided skeleton code. This involved:  
- Implementing the Q-learning algorithm for training the pirate agent.  
- Fine-tuning hyperparameters such as the learning rate, discount factor, and exploration rate.  
- Ensuring the agent could balance **exploration** (discovering new paths) and **exploitation** (using learned strategies).  
- Testing the trained model to evaluate its effectiveness in navigating the maze.  

Through this work, I gained a deeper understanding of reinforcement learning, neural network training, and the practical application of AI in game environments.  

---

### Connect your learning from throughout this course to the larger field of computer science:  
This project connects to broader computer science principles, particularly **artificial intelligence** and **reinforcement learning**. The course covered essential AI methodologies, including **Deep Q-Networks (DQNs)**, which were instrumental in developing the pirate's decision-making model.  

In the larger field of computer science, these concepts extend beyond games and can be applied to robotics, autonomous vehicles, and recommendation systems. The ability to train intelligent agents to navigate complex environments is a game-changer in multiple industries.  

Moreover, this project reinforced the importance of **data-driven decision-making**, where an agent iteratively improves through trial and error—just as AI is used in modern problem-solving, from fraud detection to medical diagnosis.  

---

### What do computer scientists do and why does it matter?  
Computer scientists apply problem-solving methodologies to develop efficient and scalable solutions. They work across various fields, including software engineering, AI, cybersecurity, and data science.  

Their work matters because nearly every aspect of modern life relies on computing, from healthcare and finance to entertainment and transportation. Whether optimizing search algorithms, designing secure encryption methods, or developing AI-driven applications, computer scientists drive technological advancements that improve efficiency, security, and accessibility in digital systems.  

In this project, we saw how reinforcement learning can enhance decision-making in uncertain environments, a skill that has direct implications in fields like robotics and logistics.  

---

### How do I approach a problem as a computer scientist?  
The key to solving problems in computer science is **structured thinking**. I approach problems using these steps:  

1. **Define the Problem Clearly** – Before writing any code, I identify the problem scope and constraints. In this case, the challenge was designing an AI agent that could efficiently navigate a maze.  
2. **Break the Problem into Components** – I analyze the system’s parts, such as environment representation (the maze), decision-making (reinforcement learning), and training methodology (deep Q-learning).  
3. **Choose the Right Algorithms** – Selecting the right approach is crucial. Here, reinforcement learning was appropriate because it allows the agent to improve over time.  
4. **Iterate and Optimize** – Once the initial implementation is complete, I refine the model by adjusting hyperparameters, improving efficiency, and testing edge cases.  
5. **Evaluate and Adapt** – Finally, I test the solution under different conditions, analyze performance metrics, and iterate as needed.  

This structured approach ensures robust, scalable, and effective solutions to computational problems.  

---

### What are my ethical responsibilities to the end user and the organization?  
Ethical considerations are vital in AI and software development. My responsibilities include:  

- **Transparency & Fairness** – AI models should be interpretable and free from biases that could lead to unfair decision-making. In this project, ensuring the pirate AI follows logical learning patterns is a small-scale example of broader AI fairness principles.  
- **Data Privacy** – If real-world data were involved, protecting user information would be crucial. While this project used a simulated environment, in actual AI applications, responsible data handling is a priority.  
- **User Experience & Safety** – The AI should enhance the user experience rather than create frustration or unintended consequences. This is especially important in high-stakes applications like self-driving cars or medical AI.  
- **Integrity & Honesty** – Whether working in research or industry, developers must ensure their systems function as intended and do not misrepresent their capabilities.  

