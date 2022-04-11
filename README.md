# PCD8544 Graphical LCD Designer

PCD8544-designer is a HTML5 web application for designing bitmaps and fonts for the PCD8544 graphical lcd. 
Encoded bitmaps and fonts work well with Adafruit's PCD8544 arduino library. This web application was written
for my own use and was designed to run locally on my own computer. I tested it with recent releases of
Firefox, Safari, and Chrome. I did not test it in IE, nor do I intend to do so. 

## Legalese:

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

## Usage:

- Draw a line between the last pixel and the current pixel by holding down the shift key.
- Undo with ctrl-z or command-z. No redo yet.
- Save and restore bitmaps/fonts from local storage
- Export/Import all saved items to/from a JSON file
- Drag and drop an image on the canvas (with canvas dimensions set to 84x48) to write a dithered approximation of the image to the display
- Current quantization/dithering techniques available: Floyd-Steinberg, Atkinson, and Sierra Lite (Sierra-2-4A), and Threshold

## Credits:
- Based on work from parent fork
