# DQN_Cart_Pole

OpenAI gym cartpole example using Deep Q Learning. Written in Pytorch.

## Introduction

* The `action` space for this problem consists of two actions: applying a force to the cart in the left or right direction.
* The `reward` function returns +1 for every time step. The entity dies if the pole falls over or if the cart gets too far from center.
* The `state` space consists of 4 real values
