# Game

I have created a game in which i used ThirdPersonController (NPC) and FirstPersonController (FPS). I created an FSM for NPC. In this game firstly my ethan is in IDLE state. When i started moving my FPS, ethan starts to run and i as a FPS starts chasing ethan means my state changes to RUNNING state . Meanwhile i can eat the tablets which increases my health to +1 and if i collide with hurdle my health will be decremented to -10 and my state changes to DEAD state and when my heatlh becomes 0 my states changes to GAMEOVER and game ends.
