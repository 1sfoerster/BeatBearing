This folder contains code for processing:
 
Processing displays the vertical line and circles underneath balls on a monitor underneath the beat bearing board.

BeatBearing_Processing.pde is the driving class 
	the line called boolean TestWithOutArduino= true; enables testing without the arduino or beat bearing board

TBearing actually draws circles

TTime draws the lines

serial_input is where you will have to put the com port, is where the arduino input is parced into boolean ball positions
or random numbers are made up if the arduino is not present.

setGrid enables use of the mouse to stretch the displayed grid underneath the physical grid

-------------------------------------------------------------------------------------------
Next Steps .. once arduino code is actually reading ball values  
<!-- language:     
	BeatBearing_Processing ....   

			turn boolean TestWithOutArduino= true; false so it will listen to the arduino  
  
			adjust maxMetronome with same value that is used in arduino code  
  			
			change the default grid dimensions to match the beat bearing board built for setGrid  
    			
	serial_input  
  	
			put balls down one at a time one the board and adjust the barray[].on mapping      
lang-none -->    
