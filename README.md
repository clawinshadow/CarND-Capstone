* Notes to reviewer
It's my individual submitting and not as a team.

My account: glorialife@gmail.com
My Name: Huang Fan

** What did I do
I simply follow the walkthroughs and the car will follow the designated waypoints along a road, recognizes the traffic light status from the ground truth data sent by simulator, stop on red and restart driving on green. 
The car was finally tested on simulator highway track, and it works fine. Because the latency problem when the simualtor sending camera images, I decrease the ros rate to 10hz in `waypoint_update.py`, or else the car's control will be erratic.

It should not be tested on real Carla, because I didn't implement a deep-learning object detection model, it cannot recognize traffic lights. 
