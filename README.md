# e-piano-game
This C++ code creates a simple piano game using the SFML library for graphics and audio. Here's a concise breakdown of what the code does:

** Window Creation :
It creates a window titled "My Piano" with dimensions 976x336 pixels using SFML.

** Texture and Sprite Setup:
Loads a piano layout image (pianoLayout.jpg) into a texture and assigns it to a sprite for display.

** Key Position Mapping:
Defines the positions of black and white piano keys using IntRect objects, which represent rectangles on the sprite for detecting mouse clicks.

** Audio Loading:

Loads audio files for white and black keys into SoundBuffer arrays (audioForWhitekey and audioForBlackkey).
Assigns these audio buffers to Sound objects (soundForwhite and soundForblack).

** Key Mappings:

Maps keyboard keys to corresponding black and white piano keys using unordered_map for both black and white keys (blackKeyMappings and whiteKeyMappings).

** Event Handling:

Mouse Clicks: Detects mouse clicks on the piano sprite and plays the corresponding sound for the clicked key (either black or white).
Keyboard Input: Detects key presses on the computer keyboard and plays the corresponding sound for the pressed key (either black or white).

** Main Loop:
Runs a loop to keep the window open, handle events, clear the window, draw the piano sprite, and display updates.


In essence, the code provides an interactive virtual piano where users can play notes by either clicking on the piano keys displayed on the screen or pressing corresponding keys on the computer keyboard.
