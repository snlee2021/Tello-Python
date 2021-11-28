# Tello-Python


https://github.com/snlee2021/Tello-Python.git

self.telloUp(self.distance_bar.get())

update the self.distance on line 32 to 0.2 or bigger.

I found when trouble shooting these scripts it is handy to uncomment the print out the return of the commands from the tello in the tello.py line 87. 

This is how I saw the tello was returning out of range always:

print(self.response)
