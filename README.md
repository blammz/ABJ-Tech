# ABJ-Tech

What is the problem that you will be investigating? Why is it interesting?

Our company, <insert name here>, will be investigating the game of Connect X, and finding the most efficient way to win the most games of Connect X.  Connect X is a very meticulous game that involves a lot of strategy and planning, and it will be interesting to simulate what move is the best in certain situations and determine what is the best course of action towards victory.

What reading will you examine to provide context and background?

The Kaggle competition website for Connect X provides a great start for the overview and background of the question at hand. Other websites are also available to aid us, such as Pascal Pons's article "Solving Connect 4: How to Build a Perfect API" (http://blog.gamesolver.org/solving-connect-four/01-introduction/)  and Gilles Vandewiele's article "Creating the (nearly) perfect connect-four bot with limited move time and file size" (https://towardsdatascience.com/creating-the-perfect-connect-four-ai-bot-c165115557b0), which both provide valuable information about what we are trying to achieve.

What data will you use? If you are collecting new data, how will you do it?

The Kaggle competition website has multiple data sets from various collaborators in the competition, which we can observe and utilize to solve our issue.
  
How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?

Running the game of Connect X many times, we can keep track of how many times the computer wins and how long it takes to make a move, and we can make a graph relating time taken to make a move and win rate.  We can compare our results to the results of other competitors and see how much more efficient they are, along with other methods of evaluation

What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? 

We will use a decision tree induction technique that can always discover a hypothesis that completely fits the training data) that outputs the optimal move for a given sequence of a certain length. This decision tree can be deserialized very efficiently by traversing the tree breadth-first and storing the information of the nodes.
