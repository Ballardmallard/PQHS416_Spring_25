PQHS 416 Spring 2025. 

First Assignment, HW6_Stockdale: A couple of notes:
1. It needs to be run with the attached .pkl file for the bot adversarial dialogue ('BAD') script to work properly.
2. I wrote this in Google Colab since I was having issues with Anaconda and the 'BAD' package from the tensorflow_datasets.
3. For question 3 I tried to implement a neural network with two hidden layers of 16 nodes, and one output layer. I changed the ReLU activation function for the hidden layers and a sigmoid activation for the final output layer (since it's a 0 vs. 1 output). To compile the the neural network, I used adam as the optimizer and binary cross entropy as the loss method.
4. I've been watching some videos from free code camp - I tried to experiment with using a dropout feature in the model. I tried different values from 0.1 to 0.5. I ended up going with 0.5 since it seemed like I got the best result w/ regards to accuracy/loss. 
