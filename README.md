# Air-Drawing

### My attempt on augmented reality with air drawing. 

# How this works

- I trained the You Only Look Once(YOLO) model to find a hand in the frame. <br>
- Then I trained the keras retinanet model to find fingertips in an image of a hand. <br>
- Then the code checks if the user is showing only an index finger.
- Then the coordinate of the index finger in each frame is stored.
- Then all of the coordinates coordinates are connected.

# To draw

- Make sure our entire hand is in the frame <br>
- Raise only your index finger to start drawing <br>
- Raise all five of our fingers to clear the screen