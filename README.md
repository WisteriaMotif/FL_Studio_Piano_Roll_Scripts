# Wisteria Motif's FL Studio Piano Roll Scrips
A collection of my python scrips for the FL Studio Piano Roll.   
*(Well, for now there is only one script, but who knows.)*

## Advanced Velocity Fades
[Link to FL Studio Forum post.](https://forum.image-line.com/viewtopic.php?t=311614)
![Advanced Velocity Fades preview image](https://github.com/WisteriaMotif/FL_Studio_Piano_Roll_Scripts/assets/143191748/d9076409-efb6-40c7-8eb1-8c1b2ed96f4b)

- Velocity L/R: The velocity of the leftmost/rightmost note(s).
- Dynamic: The overall dynamic of the notes. The default value is 1. Values over 1 will increase the dynamic.
- Dynamic Pinch: Reduces the dynamic towards the outmost notes. Values below 0 will pinch towards the left, while values over 0 will pinch towards the right.
- Curve: Adds a curve to the fade.
- Zero Velocity Protection: Stops notes' velocity from becoming 0. Helpful for instruments that simply don't play notes when the velocity is 0, yet you still want the notes audible.
