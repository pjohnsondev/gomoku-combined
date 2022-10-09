# gomoku-full-stack

## Description
This is an application we were required to build as part of my IT degree at UNE.
The game follows the rule of Gomoku found [here](https://en.wikipedia.org/wiki/Gomoku#Rules)

## Structure
There are two separate repositories attached. Cloning this repository will not provide the submodules.
Submodule urls can be found in the .gitmodules file. 
Run ``git clone <submodule url>`` for each submodule in order to have the submodules populated in the folder structure

## Operation
At present each submodule must be run separately.

The express submodule requires a .env file that contains:
1. the port to be used
2. the dbURI
3. the access token private key
4. the access token public key
