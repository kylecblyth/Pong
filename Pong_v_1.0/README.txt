=================================================================================
=================================================================================
		             PPPPPPP    OOOOOO   NN    NN   GGGGGG 
		             PP    PP  OO    OO  NNN   NN  GG    
		             PPPPPPP   OO    OO  NN NN NN  GG   GGG
		             PP        OO    OO  NN  NNNN  GG    GG
		             PP         OOOOOO   NN   NNN   GGGGGG
=================================================================================
=================================================================================

DESC:
	Two player Pong game. There is no AI at the moment. AI is planned for future
	build. Score to win is 10, after which the game restarts at 0
	
CONTROLS:
	Player 1:
		A / Z for up/down, respectively
	Player 2:
		K / M for the same.
	
	General:
		ESCAPE will exit.
		
KNOWN BUGS:
	1. Sometimes the ball will spawn with no Y speed (players can leave paddles in 
	the same spot until the next bug occurs)
	2. The ball speeds up after each paddle hit (this was intended). The bug is 
	after a certain speed is reached the ball will go right through a paddle and
	cause a score.