# AI_Flappy_Bird

NAME: VED VISHAL MIRJANKAR <br/>
PROJECT: AI PLAYS FLAPPY BIRD <br/>

ABSTRACT: <br/>
Configuring an AI Model using Python which can train itself to play the game of Flappy Bird where the bird has to pass between the pipes on the screen without touching them so as to increase the score. The game of Flappy Bird will also be coded in Python using Pygame module. <br/>

BRIEF PROCESS DESCRIPTION:<br/>
•	Built the graphics for Flappy Bird using Pygame module in Sublime Text Editor. The code contains comments for self-understanding purposes.<br/>
•	ALGORITHM: NeuroEvolution of Augmenting Topologies (NEAT):<br/>
The NEAT algorithm is an evolutionary algorithm that is used to create artificial neural networks. It uses Mutation: The program chooses one fit individual to create a new individual that has a random change from its parent and Crossover: The program chooses two fit individuals to create a new individual that has a random sampling of elements from both parents. Detailed information is given in this link: <br/>
https://nn.cs.utexas.edu/downloads/papers/stanley.cec02.pdf<br/>
  1.	Inputs: Bird Y, Top Position, Bottom Position
  2.	Outputs: Jump, Don’t Jump
  3.	Activation Function: tanH
  4.	Population Size: 50 birds
  5.	Fitness Function: Distance
  6.	Max Generations: 30<br/>
•	Downloaded and made changes to the NEAT Configuration File. Detailed information is given in this link:<br/>
https://neat-python.readthedocs.io/en/latest/config_file.html<br/>
•	Coded and implemented the NEAT Algorithm into the python file. The code contains comments for self-understanding purposes.<br/>
•	Modifications were made later on to improve how the game looks.<br/>

IMAGES:<br/>
1.	Shows how the project looked initially where the bird passes through the pipes regardless of collision. Score also increases as the bird passes each set of pipes. (Only the graphics part)<br/>
![image](https://github.com/vmirjankar/AI_Flappy_Bird/assets/111427005/81729bc7-460c-4ffb-81f9-cda221bb0738)<br/>
2.	Shows how the final project looks after configuring the NEAT algorithm and implementing it. (Full project)<br/>
![image](https://github.com/vmirjankar/AI_Flappy_Bird/assets/111427005/7657bc50-36af-4427-b714-bcc85ecdaae8)<br/>





