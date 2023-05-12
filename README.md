# ReinforcmentLearningTTTOE

<b>This is all entirely from scratch. No RL libraries. A working tic-tac-toe game environment, state and value function management system,
  and monte carlo training. </b>


Version 1 capabilities:

Offers a scalable game environment for playing tic-tac-toe of any n sized board
A training environment placing CPU against CPU for N episodes using fixed policy monte carlo afterstate learning
Exports models in dictionary format consisting of states and values (which can easily be exported as a JSON file) 
Allows one to play live against the model.
Manages to get good at 3x3 tic-tac-toe in less than 5 minutes

Training code is highly modular allowing for many various tweaks either immediately through a change in parameters 
or through easy code edits. 

Immediate Next Step Plans:
Rewriting the code in Rust for faster training times
Implementing monte carlo control for dynamic policy tuning
Develop visualizations and higher precision metrics for comparing model performances
Consider 4x4+ versions of tic-tac-toe & multi-move (being able to move twice per turn) tic-tac-toe

Further Next Steps:
Utilize more advanced RL algorithms
The environment has been set up with the implementation of future algorithms in mind. A lot 
of the code will hopefully not need to be rewritten. 

