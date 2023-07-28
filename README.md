# SumoBot
A robot designed with the intentions of pushing opposing robots out of a ring. Built from scratch (chassis, PCB, hardware, programming, etc.) with an Arduino. In this project, I applied my knowledge of the Arduino programming language (which is essentially C++) and the basics of handling hardware. PLEASE WATCH VIDEOS FOR CLEARER VISUAL.

Sumo Bot Battling Rules:
- Must stay within the black "battleground" surrounded by a white border
- Robots are either placed side-by-side (to the right of each other) or back-to-back
- 20cm x 20cm x 20cm (before the round starts)
- under 2kg
- 5 sec delay before any movement

Robot Criteria:
- at least 1 ultrasonic sensor (to detect distance of opposing bots)
- at least 1 phototransistor (to detect battle white ring border) with a pairing super bright LED
  - when bright light is detected, the bot is at the edge of the ring (AKA DANGER!)
- two motors controlled by a motor driver (for the wheels)
- Lithography, drilling, soldering for the PCB
- Self-made plastic chassis (cutting, bending, drilling)
- Wiring, connections, troubleshooting for the motor driver, sensors, PCB and motors

Extra features:
- extra ultrasonic sensor to allow pre-battle decision-making
  - triggers different functions for when the opponent is behind or beside
- 1 extra motor and magnets to control the fold-out plastic sheet
- white plastic sheet that folds down
  - triggers opposing bots' line detection function (tricks opponent into moving backwards (out of the ring))
  - causes slipping to opponent wheels
  - reveals "angry game face" >:D

The purpose of my team's design was to not heavily rely on software or brute strength for an advantage in the ring, but to rely on design and timing. We utilize the 5 second delay at the beginning of each round to determine the starting position of the robot and following up with the corresponding but simple function. With this pre-battle decision-making, our bot wasted no time to make contact with the opponent. 
Additionally, the design of the fold-out plastic sheet grants an advantage where instead of the opposing bot working against us, the white colour of the plastic prompts their defensive function that tricks the opposing robot into moving backwards (out of the ring) by themselves.
  
