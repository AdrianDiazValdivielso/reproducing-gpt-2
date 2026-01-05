This is a personal project of mine, where I reproduce OpenAI's GPT-2 model from scratch to better understand the working principles behind Large Language Models. It's still a work in progress.

I followed a tutorial by Andrej Karpathy: https://www.youtube.com/watch?v=l8pRSuU81PU
My inspiration to start this project come from the following Looking Glass Universe video: https://www.youtube.com/watch?v=HswlqMnQ6oE 
Really useful weppage for the visualization and understanding of the GPT architecture: https://bbycroft.net/llm

# 2026/01/05
Initialized weights and biases to appropriate values (we want to keep the forward pass signal's mean at 0 and variance at 1).