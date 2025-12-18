# DreamWaQ: sim2sim_go2

## Description
This repo contains implementation of the paper [Learning Robust Quadrupedal Locomotion With Implicit Terrain Imagination via Deep Reinforcement Learning](https://arxiv.org/abs/2301.10602)

This project can run on the Windows system. It is recommended to use Mujoco 3.2.7

There are some files in utils that are not actually used – you can ignore them, but some of the contents might be useful to you.

## Sincerely thank the original authors of the repositories:

1. https://github.com/Manaro-Alpha/DreamWaQ
2. https://github.com/ShengqianChen/DreamWaQ_Go2W 
3. https://github.com/LucienJi/MetaRobotics
4. https://github.com/InternRobotics/HIMLoco
5. https://github.com/yusongmin1/My_unitree_go2_gym

## How to use

1. create a python env, install pytorch, numpy, mujoco 3.2.7, pynput
2. use scripts/dreamwaq_go2.py

The arrow keys control the quadruped robot's forward/backward movement and left/right translation, while the Q and E keys control its left/right rotation.
