# The_Outliers

#### Movement of Single Bot (Movement_single.ipynb) 

This project implements the A* algorithm to determine the shortest path for a single bot moving from a given source to a destination within a grid. The bot's movement is tracked and displayed step by step with directional commands.

##### Key Features:
- The bot starts by facing upward.
   - Movements are printed in a sequence of actions such as:
      - Forward: Move in the current direction.
      - Left: Rotate 90° counterclockwise.
      - Right: Rotate 90° clockwise.
When moving in a different direction (e.g., from facing upward to moving right), the bot first changes its direction (via left or right turns) and then proceeds forward.
By applying the A* algorithm, the bot calculates the optimal path considering obstacles and efficiently reaches its destination.


#### Coordinated Movement of Dual Bots (dual_bots.ipynb)

This notebook implements the A* algorithm for navigating two bots from their respective sources to destinations. In case both bots encounter a potential collision, one bot will wait while the other proceeds, ensuring safe and efficient movement for both.


#### GUI display of two bots (gui_dual.ipynb)

This notebook implements the visualization of A* algorithm for navigating two bots using a grid matrix with tkinter


#### Used Q-Learning Approach for Multi Bots (q_learning_bot.ipynb)

This notebook implements Q-Learning for receiving dynamic number of bots from respective user along with exploring possible solutions and gives faster response by finding the firsst approach to destination and stopping there saving both time and resources.


#### Final Code (q_learning.ipynb)

We implemented our Q-Learning algorithm and optimize our outputs in this file.
It includes outputs including
- Time Taken
- Average Steps
- Each Bot's individual steps
