# Microbit project
By: Caleb and Akram

Reference URL's:

  - https://microbit-micropython.readthedocs.io/en/latest/audio.html
  
  - https://microbit-micropython.readthedocs.io/en/latest/music.html

  - https://microbit-micropython.readthedocs.io/en/latest/music.html#example

Description of __CODE__:

  - We have written some code using python that is run on the microbit to play different sounds and tone in various sequences to overall create a beat for your ears, you will have to connect the microbit to an output audio device such as headphones of speakers.throughout the programme when running we have made various displays using the LED lights on the microbit.
  
__code__:

  -from microbit import *
  
import music

music.play(music.NYAN)

music.play(music.CHASE)

display.show(Image.HEART)

display.show(Image.HEART_SMALL)

display.show(Image.HAPPY)

display.show(Image.SMILE)

notes = ['c4:1', 'e', 'g', 'c5', 'e5', 'g4', 'c5', 'e5', 'c4', 'e', 'g', 'c5', 'e5', 'g4', 'c5', 'e5',
        'c4', 'd', 'a', 'd5', 'f5', 'a4', 'd5', 'f5', 'c4', 'd', 'a', 'd5', 'f5', 'a4', 'd5', 'f5',
        'b3', 'd4', 'g', 'd5', 'f5', 'g4', 'd5', 'f5', 'b3', 'd4', 'g', 'd5', 'f5', 'g4', 'd5', 'f5',
        'c4', 'e', 'g', 'c5', 'e5', 'g4', 'c5', 'e5', 'c4', 'e', 'g', 'c5', 'e5', 'g4', 'c5', 'e5',
        'c4', 'e', 'a', 'e5', 'a5', 'a4', 'e5', 'a5', 'c4', 'e', 'a', 'e5', 'a5', 'a4', 'e5', 'a5',
        'c4', 'd', 'f#', 'a', 'd5', 'f#4', 'a', 'd5', 'c4', 'd', 'f#', 'a', 'd5', 'f#4', 'a', 'd5',
        'b3', 'd4', 'g', 'd5', 'g5', 'g4', 'd5', 'g5', 'b3', 'd4', 'g', 'd5', 'g5', 'g4', 'd5', 'g5',
        'b3', 'c4', 'e', 'g', 'c5', 'e4', 'g', 'c5', 'b3', 'c4', 'e', 'g', 'c5', 'e4', 'g', 'c5',
        'a3', 'c4', 'e', 'g', 'c5', 'e4', 'g', 'c5', 'a3', 'c4', 'e', 'g', 'c5', 'e4', 'g', 'c5',
        'd3', 'a', 'c4', 'f#', 'c5', 'd4', 'f#', 'c5', 'd3', 'a', 'd4', 'f#', 'c5', 'd4', 'f#', 'c5',
        'g3', 'b', 'd4', 'g', 'b', 'd', 'g', 'b', 'g3', 'b3', 'd4', 'g', 'b', 'd', 'g', 'b']
tune = ["C4:8", "D4:9", "E4:10", "C4:7", "C4:8", "D4:7", "E4:9", "C4:10",
        "E4:8", "F4:9", "G4:7", "E4:8", "F4:9", "G4:10"]
        
music.play(notes)

music.play(tune)

  
  __SENSORS and CHARACTERS USED__:

  - The python code we have develpoed uses the following to be carried out:
  
    1) Processor
    
    2) LED lights
    
    3) USB connector
    
    4) Wire
    
    5) Output audio (speaker or heaphones)
    
    6) Computer
    
    7) Microbit
    
  
Screenshots of __CODE__:
![Pic](https://github.com/AMOAD2003/Akram-Mahad/blob/master/unnamed.jpg "import music")

![Pic](https://github.com/AMOAD2003/Akram-Mahad/blob/master/unnamed%20(2).jpg "tone and notes")

![Pic](https://github.com/AMOAD2003/Akram-Mahad/blob/master/unnamed%20(1).jpg "music") 

__CODE__ and test:
  - to test the code to see if it worked properly we used a home-made headphone system where we used two wires and placed them on the      jack of the headphones cable and then connected it to the ground and 0 ports on the microbit which allowed us to hear the different      tones that we programmed it to produce.
  - we the coppied the code from the python writing website onto the microbit to run through its programme.
  
__changes made__

  -we changed the notes that are played and added in some images that can be displayed using the LED's on the microbit.
  
Ideas for expansion:
  - you could expand this project by using the code above and altering it to create different audio outputs, this could also be expanded     so that it can be interactive with you, allowing you to press buttons and play two differnet outputs at the same time.
  see link for help- https://microbit-micropython.readthedocs.io/en/latest/tutorials/buttons.html
  
  
