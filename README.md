# Cartpole-Agent

AI agent that plays the 2D game Cartpole.

This program is written in python and uses the openAI gym enviroment as a basis for the game.
With the optimal weights loaded, the agent balances the pole on top of the cart until the maximum score is reached.
If no weights are loaded the deep Q learning model will train itself to play the game, converging at the maximum score, saving this version to the weights file.
