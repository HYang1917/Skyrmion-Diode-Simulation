## Skyrmion-Diode-Simulation

All simulations were conducted in [MUMAX3](https://mumax.github.io/), using GoogleColab. It is required to use a NVIDIA graphics card with CUDA. 
# File Name Structure
All the folder follows the format of " $x$ nm LR", where $x$ is the skyrmion size, and LR/RL stands for the skyrmion travel direction. LR: Left to Right; RL: Right to Left. 

Under mumax3_script folder, there are two .txt file. The SOT.txt is the file prepared to simulate 10nm skyrmion and 20nm skyrmion, while the Ku is not set in this file. The Ku can be tuned to reached the ideal skyrmion diameter. The skyr_3.txt is the script for 3nm skyrmion.
