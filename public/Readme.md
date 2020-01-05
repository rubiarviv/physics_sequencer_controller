Description: In this controller you'll choose 4 notes that will be assing to 4 balls bounded in a rectangle,  and will play a sequence of each note when his corresponding ball will touch the edge of the rectangle.

ID: physics_sequencer_controller

input messages: 
channels - none.

output messages: 
1.note-on - sent when a note is played:
 channel name: 'midi'
message parameters: 'note-on' , note [0...127], velocity

2.note-off - sent when a note is released
 channel name: 'midi'
message parameters: 'note-off', time, note [0...127], velocity 