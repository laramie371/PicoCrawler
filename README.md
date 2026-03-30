This game runs on the Raspbaerry Pi Pico with an SSD1306 series screen installed. No other hardware needed.

You start as a hero in a dungeon and encounter various enemies and items. Each killed enemy gains a point, but
fighting brings the risk of death. Swords give a point, potions can give or take a point, and shields protect you 
from the next potential death. Your current score and high score are displayed at the top and on death. The 
terrain is randomly generated. 

To install, you will need to use software like Thonny. Copy main.py to a new file in Thonny and click Save as,
main.py on the Pico. Then do the same for the ssd1306.py driver, saving it with the respective name on the Pico. 
The game will generate another file on the Pico called high.txt which contains your highscore and can be deleted
to reset the highscore. The game assumes you are using the standard GPIO Pins(4-5). If you are using different 
pins you must change this in the game. Use Ctr+F to find this comment 
"#YOU MUST SET CORRECT PIN LOCATIONS BELOW "

