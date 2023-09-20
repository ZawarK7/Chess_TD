# Chess_TD

This Python script demonstrates reinforcement learning using Temporal Difference (TD) learning in the context of chess. The program uses a simple TD(0) learning algorithm to make strategic decisions during a chess game.


Overview:
The script initializes a chessboard and defines TD learning parameters such as the learning rate, discount factor, and the number of episodes for training. It then proceeds to learn by playing games against itself. The reinforcement learning algorithm aims to maximize material advantage, represented by predefined piece values.


Key Features:

Chessboard Representation: The chessboard is represented using the python-chess library, providing the necessary functionalities to play chess and extract game states.

TD(0) Learning Algorithm: The TD(0) learning algorithm is employed to learn the value function, representing each state's expected material advantage.

Random Move Selection: During training, the program selects random legal moves for exploration and learns from the resulting states.

Game Simulation: After learning, the program simulates a game, using the retained value function to make informed moves and assess the outcome.


How to Use:

Ensure you have Python and the required libraries installed.
Run the script in a Python environment.
Watch as the program learns and plays chess games.


Feel free to experiment with the learning parameters, piece values, and end-game techniques to observe how the agent's strategy evolves over training.
