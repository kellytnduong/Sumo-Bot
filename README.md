# SumoBot
A robot designed with the intentions of pushing opposing robots out of a ring. Built from scratch (chassis, PCB, hardware, programming, etc.) with an Arduino. In this project, I applied my knowledge of the Arduino programming language (which is essentially C++) and the basics of handling hardware. 

The requirements/criteria of this project:
- Must stay within the black "battleground" surrounded by a white border
- 20cm x 20cm x 20cm (before the round starts)
- under 2kg
- at least 1 ultrasonic sensor (to detect distance of opposing bots)
- at least 1 phototransistor (to detect battle white ring border)
- 5 sec delay before any movement

Extra features:
- extra ultrasonic sensor to allow pre-battle decision-making
  - triggers different functions for when the opponent is behind or beside
- white plastic sheet that folds down
  - triggers opposing bots' line detection function (tricks opponent into moving backwards (out of the ring))
  - causes slipping to opponent wheels
  - reveals "angry game face" >:D 
