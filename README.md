# Tsetlin-projects
Some projects from the course IKT457 using the Tsetlin Machine.

## Goore game
This small projects was used as an introduction to the Tsetlin Machine. Five different automata should either choose 0 or 1, with rewards and penalties being distributed based on an environment. From working together, the program will learn that the best possibility for rewards are if three of the automata choose 1, and the two remaining automatas choose 0. After multiple runs, the system will get more and more confident by shifting the states toward maximally memorized for either action 1 or action 2.    
![tsetlin1](https://github.com/user-attachments/assets/f6e30b49-46b8-4a3a-9a84-acff20db1275)    

## Cancer classification
The projects uses type 1 and type 2 feedback to classify whether a patient with a given set of parameters have breast cancer or not. The Tsetlin Machine creates the rules on its own based off a forget value and a memorize value, and learns patterns for which parameters are important when classifying the patients.    
![tsetlin2](https://github.com/user-attachments/assets/325f825a-9ec3-4378-9c0c-59875752dd30)    
In this screenshot, the tsetlin machine created three rules for each of the actions, and used them to classify the patients, and got correct in all classifications.

## Interactive stationary distribution
To visualize the distribution chart, a Literal Automaton with eigth states was created. The equations for the chart was given as follows:    
![tsetlin4](https://github.com/user-attachments/assets/dea463f9-7e9b-4372-9c45-343fc9b57016)    
Using these equations, with dynamic sliders, we could make a distribution chart based of the specificity s, and the probabilities P(Y) and P(L|Y) to vizualize the probabilities for the automaton to be in each of the states.
![tsetlin3](https://github.com/user-attachments/assets/2326797f-6747-4999-9e97-b27121033081)    

