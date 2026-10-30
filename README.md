# BreathBeat

Add details here 

The details of my project is that it is called BreathBeat and is a song that is supposed to work as a breathwork tool to help with stress and anxiety. 

I used Tunepad tutorials to aid in my understanding of how to navigate the platform. 
TunepPad tutorial links 
https://learn.tunepad.com/interactives/piano/ 
https://learn.tunepad.com/ 
https://learn.tunepad.com/learn/seven-chords/ 
https://learn.tunepad.com/docs/ 

To navigate my code, the main melody is the main part to follow: 

# Piano - Main melody to follow for breathing
# Rising notes = breathe in
# Steady notes = hold in 
# Falling notes = breathe out

# Introduction
playNote(64, beats=4, velocity=35)


# Repeat the breathing pattern 6 times
for i in range(6):

    # Breathe in - 3 beats, rising pitch
    playNote(60, beats=2, velocity=40)
    playNote(64, beats=2, velocity=40)
    playNote(67, beats=2, velocity=40)
      
    
    # Hold in - 4 beats, steady
    playNote(72, beats=2, velocity=40)
    playNote(72, beats=2, velocity=40)
    playNote(72, beats=2, velocity=40)
    playNote(72, beats=2, velocity=40)

    # Breathe out - 5 beats, falling pitch
    playNote(67, beats=2, velocity=35)
    playNote(64, beats=2, velocity=30)
    playNote(60, beats=2, velocity=30)
    playNote(55, beats=2, velocity=25)
    

# Ending 
playNote(60, beats=4, velocity=15)

This is the key feature of BreathBeat and the comments are used as instructions for TunePad to know what the reasonings are for the code and also for listeners, but they can also know through the rise and fall of the notes. 

The soft introduction and ending of the main melody act as 'warnings' in a way, sounding different and smaller durations to let you know that it is starting and ending. 

In my json file you can also see the code of the other supporting instruments but that is just for added layers to the song, it doesn't have a purpose in terms of the actual breathwork techniques. 
