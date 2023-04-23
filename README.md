Download Link: https://assignmentchef.com/product/solved-ai-python-homework-1
<br>
(Recommended: on a python jupyter notebook)

Implement “Infastructure” the main{} that runs the “simulation” of the agents Agent<sub>i </sub>acting in the world:

<ul>

 <li>State/world-situation representation</li>

 <li>main(S(t), A<sub>i</sub>(t))=S(t+1); main(S(t)){loop{for i : A<sub>i</sub>(t)=action(Agent<sub>i,</sub>S(t));</li>

</ul>

S(t+1)= for i : apply action A<sub>i</sub>(t) on S(t)}}

Implement agents that use the  various Heuristic Search Algorithms…

Instantiate your infrastructure with a single agent to solve a puzzle of your choice (no TICTACTOE…)

Write a report describing your implementations and a statistics over sample runs .

Your statistic should compare the performance of different agents running different Search Algo and/or different heuristic evaluations

Instantiate your infrastructure with two  agents to play a board game

(recommended chess)

(as before main(S(t), A<sub>i</sub>(t))=S(t+1); but now agent1 does nothing when t=even and plays a move when t=odd, and viceversa for agent2.

Instructions and recommendations:

1.Keep your implementation as modular as possible, keeping various components  (infrastructure, state representation and computation of agent actions effects, agents, search algo, Heuristic functions…) well separated from each other and/or encapsulated…

For example, it should be possible , given an implementation that plays chess, to use it to play a different game by simply changing the game model (representation and functions).

<ol start="2">

 <li>You can import existing libraries or other implementations (clearly state, when you do so, your source) as long as you clearly distinguish what you have imported from what you have created yourself.</li>

</ol>