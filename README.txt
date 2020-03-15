-----------------------------------------------

Thank you for downloading 
Pixel Generator v1.5.3
https://github.com/MegaMango64/PixGen

Developed by Mr Mega Mango

Contact:
Email @ MrMegaMango@DigDownStudios.com
Twitter @ Mr_Mega_Mango

-----------------------------------------------

***What is This***
	- This program currently has six modes of function:
		- Pixel Circle
			- This is the most basic mode. Input a desired circle width along with optional
			  X and Z coordinates of the center point and a pixelated circle will be created
			  with these requirements. 
			- Note: larger circles require longer computation times.
		- Pixel Circle+
			- This is like the Pixel Circle mode but faster. Input a desired circle width along with optional
			  X and Z coordinates of the center point and a pixelated circle will be created
			  with these requirements. This mode uses a different method for finding the pixels; it is faster
			  but not as percise. Thus it is recommended for use with larger circles, as smaller circles with this 
			  process tend to not draw as well as the standard Pixel Circle mode.
		- Spaced Points
			- This mode is for advanced applications of placing evenly spaced points around a circle.
			- Input the circle width, the number of points, the angle offset CCW from the positive X axis,
			  and the X and Z coordinates of the circle's center point and the properly spaced 
			  points will be created.
			- Using the coordinates are most helpful in this mode.
		- Line
			- This mode allows for the accurate and consistent formation of a line based only on two fixed points. Using
			  the X and Z coordinates of the beginning point and the same for the ending point a line will
			  be created between the two.
		- Polygon
			- This mode makes use of the Spaced Points and Line mode to create a regular polygon made by inscribing
			  the shape into a circle. The width corresponds to the size of the circle not necessarily the polygon's width.
			  The X and Z coordinates are of the center point. The angle offset rotates the shape CCW and the number of sides
			  is self-explanatory.
		- Rectangle
			- This mode helps to expedite the process of making rectangles. Input the X and Z coordinates of corners that make
			  up a diagonal of the rectangle and the corresponding shape will be created.

***The Menu and How to Use it***			  
	- This program now has a collapsible hamburger menu in the upper left corner for easier navigation of modes and settings.
	- Note: click on the menu to open it and click anywhere else on the screen to close it. Likewise, in any tab a different
	  tab can be selected by clicking on the related symbol.
		- Menu
			- Denoted by the three horizontal lines, left clicking on this symbol will open the menu and show all
			  available tabs. From here clicking on any other tab will open their respective menu.
		- Create
			- Denoted by the "+" symbol, left clicking on this button will open all avialable modes of function:
			  Pixel Circle, Pixel Circle+, Spaced Points, and Line. Clicking on any of these buttons will change the user
			  input section on the right section of the screen to reflect the selection.
		- Settings
			- Denoted by the gear, left clicking on this symbol will open all non hidden settings, function key settings
			  remain hidden. 
				- Clear
					- Clicking on this will remove all pixels from the room, clearing the workspace.
				- Auto Clear
					- Clicking on this will toggle ON(green) and OFF(red) if the program will clear the workspace between
					  new calculations.
					- The colored circle next to this button and the circle at the upper right will show this state.
					- The functionality of it being OFF(red) allows users to create complex shapes by chaining the modes
					  available in this program together.
				- Undo
					- Clicking on this will undo a pixel calculation.
					- When the text is dark it can be pressed. When light it cannot be pressed.
				- Help
					- Clicking on this will open a pop-up that has the mapping of the function keys and the website for 
					  further updates.
		- Plans
			- Denoted by a mallet, left clicking on this symbol will display the recording mode and playback mode.
			- In order to use Plans, Auto Clear must be disabled. The buttons will remain grayed out until changed.
				- New
					- This mode records all user inputs and saves them to a file created by the user.
						- Left clicking on New will open the file explorer.
						- It is recommended to save the Plan to a place that you will remember such as the Desktop or a folder
						  you created. As saving to the program directory or working directory may redirect your file elsewhere.
					- When recording the colored circle at the top right will blink.
					- When done recording press the Stop button to cease new inputs being saved.
						- Stop button replaces New button when recording.
				
				- Load
					- This mode allows you to load a Plan file that has recorded user input on it. This can be used to save
					  your work or get designed Plans from other users.
				
				- Load & Rec
					- This mode allows you to load a Plan file and continue recording onto it. Due to the limitations of the
					  engine you must first select the file to load followed by the location to save the new file. The loaded
					  calculations followed by any new input will be saved.
		- Color
			- Denoted by a paint brush, left clicking on this symbol will open an 2 x 8 matrix of colors.
			- Clicking on one of these 16 colors will change the pixel color for the next pixels to be created.
					  
***Plans***	
	- This is quite possibly the most powerful functionality of this program. Record and Load user input by the click of a finger.
	- Load your saves or even send saves to a friend!
	- Press the New button to begin recording. Any input will be saved such as Line Mode or Circle Mode calculations or even just
	  creating individual pixels or notes.
	- Auto Clear must be disabled to use this mode.
	- While recording clear cannot be used however highlighting then deleting pixels still works.  Likewise, Crtl+Z can be used to undo a previous step.
	- When done recording press Stop in the menu.
	- Loading is as simple as opening the file's location on your computer then waiting for the calculations to finish.
	
***Notes***
	- Notes are one of the hidden gems in this program developed due to user demand.
	- To create a new note middle click on the mouse by pressing down the wheel.
		- For trackpad users look up how to add this functionality to your computer.
	- Upon creation, the note will begin recording any key presses.
		- Pressing the ENTER key or typing # will return a line.
	- When done typing left click the green check mark to save it.
	- In order to edit a closed note left click on the blue note symbol.
	- Clicking the red X will delete the note entirely.
	- Beneath both the check and X is an eye symbol that toggles the notes visibility, this reduces its footprint on the screen.
	- Notes will be saved during the Plan recording process.
	
***Features***
	- Left click in the gray textboxes to turn them green in order to begin typing.
	- In all modes every block is designated by a X and Z coordinate making translation to
	  other applications less burdensome.
	- Hold down the left mouse button and move the mouse to drag the shapes around.
	- Scroll wheel up and down to zoom in and out.
	- Double left click on blocks to highlight them. Press delete or backspace to delete these selected pixels.
	- Single right click to create a single pixel.
	- Hit the Submit button or Enter key to run the computation.
	- Right click on the desktop icon and press "Open file location" in this location is this README.
	- Press Ctrl+Z to undo a pixel calculation.
	
***Function Keys***
	- Press the F1 key to take a screenshot. This is most likely saved under:
	   C:\Users\yourusername\AppData\Local\Pixel_Circle_Generator\Screenshots
	   - Note: AppData is a hidden folder.
	- Press the F2 key to switch between circle saving modes. By default this is OFF. When ON
	  a text file will be created after each time the Pixel Circle calculation is run. This is 
	  another way of visualizing the circle you created. A grid of 0's and 1's are created in the file,
	  the 0s are empty spaces and the 1s are the pixels of the circle. This is most likely saved under:
	   C:\Users\yourusername\AppData\Local\Pixel_Circle_Generator\SavedCircles
	   - Note: AppData is a hidden folder.
	- Press the F3 key to cycle between classic, white, and gray backgrounds.
	- Press the F4 key to center and zoom fit the view to fit all pixels on the screen.
	- Press the F5 key to cycle between standard 1024 x 768 and maximized screen size. (This may not work
	   as expected on a device to device basis.)
	- Press the F6 key to activate my favorite hidden feature.  Once activated the user will be prompted to save a .png to the computer,
	   in this image file will be the entirety of the pixels created in the program at the time of activation.  Pixel colors will be properly
	   observed and recorded.
	- Press the F7 key to run an area calculation inside a closed shape.  The resulting pixels that make up this area will
	   be dispalyed at the bottom left.
	- Press the F8 key to import a custom map/background.  First right click on a pixel with a known coordinate, next type the x coordinate,
	   and then type the z coordinate. The image will then be moved to its proper location.  This feature is included when recording a plan.
		- Pressing F8 when a custom background is present will toggle its visibility.
		- Pressing Shift+F8 will delete the old background and ask for a new one.

***Limitations***
	- Larger circles will take longer to compute and creating even bigger circles may even
	  cause an error that crashes the program.
	- Creating circles larger than 32,000 width will result in failed computations
	  for standard Pixel Circle mode. Pixel Circle+ might be able to though!
	- Computation speeds and size limitations are device dependent.
	- Screen resolution of greater than 1024 x 768 required.
	
	
***Extra***
	- Like this program or found a bug? Let me know!