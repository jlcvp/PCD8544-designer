# PCD8544 Graphical LCD Designer

PCD8544-designer is a HTML5 web application that provides a visual reference to generate code in C for the PCD8544 display module (nokia 5110).
You can save your artworks and load them later, (it uses only the browser's local storage and no data is ever uploaded). Use it for designing bitmaps and fonts for the PCD8544 graphical lcd. 

Encoded bitmaps and fonts work well with Adafruit's PCD8544 arduino library. 

This web application was written
for my own use and was designed to run locally on my own computer. I tested it with recent releases of
Firefox and Safari. I did not test it in Edge nor Chrome but it should work as well.

## Usage:
### Live version
The project is deployed to firebase hosting at [https://PCD8544designer.web.app](https://pcd8544designer.web.app/)  
A mirror can be found on github pages [jlcvp.github.io/PCD8544-designer](https://jlcvp.github.io/PCD8544-designer/src)
### Features
- Draw a line between the last pixel and the current pixel by holding down the shift key.
- Undo with ctrl-z or command-z. No redo yet.
- Save and restore bitmaps/fonts from local storage
- Export/Import all saved items to/from a JSON file
- (TO-DO) Drag and drop an image on the canvas (with canvas dimensions set to 84x48) to write a dithered approximation of the image to the display
- (TO-DO) Current quantization/dithering techniques available: Floyd-Steinberg, Atkinson, and Sierra Lite (Sierra-2-4A), and Threshold

## Credits:
- Based on work from parent fork [pinsonn/st7565-designer](https://github.com/pinsonn/st7565-designer)

