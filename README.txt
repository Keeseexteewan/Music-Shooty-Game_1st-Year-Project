A project I made for my first year of Uni. 
Coded in Processing 3 using the Java language. 
Uploaded to GitHub for posterity. 
This description is an attachment to the original README file. 

Project description: 
A technically "infinitely" replayable top down shooter/ bullet hell. 
This is because of the semi random nature of the spawns. 
But mostly due to the timing of the spawns being based on the 
bgm of the game. 
The bgm is replaceable by the user by replacing the "bgm.mp3" file with a different track. 

NOTE: For the GitHub upload "bgm.mp3" has been removed to keep the size small. 
Please add this back or else the game won't run. 


** START OF OLD READ ME FILE ** 

THINGS TO NOTE ABOUT bgm.mp3:
 - AT THE MOMENT ENEMIES DO NOT SPAWN IF "bgm.mp3" IS NOT PRESENT
   The current bgm should be Moonlight Sonata by Beethoven, but 
   feel free to experiment on what kind of music you use. 

 - Place any mp3 file in Data/sounds of the game's directory and rename it 
   "bgm.mp3". This should make it automatically playable by the game. 
   Like seriously... make sure it is there before starting.

 - The game uses the beats of "bgm.mp3" to spawn enemies, the difficulty 
   and length of the game may be determined by the how fast or bass heavy the song is. 

 - The beat detection algorithm I'm using (A.K.A, the default minim one) is not 
   the most accurate when it comes to detecting beats so again, the song
   will most likely determine the difficulty and length of the game. 
   It appears to like songs with large variations in sounds. 

 - I have not tested this with vocal tracks so... yeah. 

 - Songs Tested with this game: 
	- Moonlight Sonata          - Beethoven    (Classical Piano)  
	[Slow but consistent enemy spawn through the first movement
	 a bit boring, but at least it's predictable]

	- Alf Layla wa-Layla        - Ecriss       (DnB) 
	[Didn't really work well with this one, or any DnB for that matter] 

        - Feel That Bad Apple Beat! - Violet Delta (Synthwave) 
	[Faster enemy spawn, more difficult right off the bat; apparently 
	 has a lot of beats that game cannot identify as hat, kick or snare] 

Other stuff that might be useful to note:

 - I completely understimated the amount of code that needs
   to be implemented for the music part of the game to work.
   In the end I kinda just shoehorned the code in... 
   So if that is not working, or is buggy. 
   I apologize, this is super unfinished.  Some parts of 
   the game don't even scale to the resolution properly yet. 

 - There is a file called "game.xml", it handles a couple 
   of game settings and maybe other things that I have
   added after the fact that I've written this. 

 - Game Controls: 
	*Movement:  		  Arrow keys
	*Shooting:  		  Space
        *Half Movement Speed:	  Shift
	*Exit game: 		  Escape Key (This should be a temporary thing) 
	*Continue Game when dead: r


