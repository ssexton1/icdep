# Admin:
## Problem
How can we ensure that each card is received once and only once?
## Solution
To send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network the bottom right of the front of the card will contain the instructions along with the target node. By including a target node along with the instruction, nodes along the way can be given instructions instead of only Bob receiving instructions from Alice. If a star * is included instead of the UWNetId of a specific node then every node along the way shall listen to the command. Each node should respond with a new card that has a body message giving their response and if the command was successfully completed or not along with their UWNetId.
