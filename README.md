This is a simple game that resembles Super-Mario and it is created using Micrblaze and user-defined IP to generate a VGA displayer.
General description: The scene has a background with mountains and a sun, the character is located on the lower side of the screen and it is enabled auto-move. user only needs to use W key as jumping to operate on                         this game. Additionally, there are randomly generated buff which have three colors, red represents slow-down, yellow represents speed-up and black represents an alternate speed. 
Screen shot from the actual test:
![ff420632022c49b0ca5379afdf54e99](https://github.com/user-attachments/assets/ecce0d16-015e-4340-9de4-c043e7603443)
![0e000b7ebed86b7fb37c57737e278e8](https://github.com/user-attachments/assets/bd632a6d-b577-44e4-abd5-89d541effafb)

How to operate on this game:
This is divided into two parts:
part1: in vivado, open the .xpr file and generate bitstream to get the block diagram version of the game design, this will create an .xsa file which contains the information. 
Part2: you should move this .xsa file into the Vitis as the base file and then use the featured functionality to build the project and then run the project.

Note: This constraint is based on the urbana board regulation which has a calrification on the website attached below:
https://www.realdigital.org/doc/496fed57c6b275735fe24c85de5718c2#seven-segment-display

when operating the game, the user needs a HDMI line, one side to connect to the VGA display(general screen) and the other side connected to the FPGA board to display the output of the game.
