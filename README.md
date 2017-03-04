Dataset of Salient Closed Boundary Tracking
====

This dataset contains nine video sequences captured by webcam for salient closed boundary tracking.They are used in our paper<br>
	` "Real-Time Salient Closed Boundary Tracking via Line Segments Perceptual Grouping, Xuebin Qin, Shida He, Camilo Perez Quintero, Abhineet Singh, Masood Dehghan and Martin Jagersand." `<br>
which is submitted to IROS 2017.

![Tracker_Initialization image]{Tracker_Initialization.png}<br>

FPS: 30<br>
Frame size: 640(width) x 480(height)<br>
There are 9598 frames in total.<br>

Frame number of each sequence: <br>

1.BookStand.avi:		899<br>
2.Bowl.avi:			1079<br>
3.GarbageBin.avi:		924<br>
4.MarkCup.avi:			859<br>
5.MarkCupContour.avi:		1226<br>
6.MarkCupPourWater.avi:		971<br>
7.NonplanarBowl.avi: 		1454<br>
8.ToolBox.avi:			1135<br>
9.TransparentCup.avi: 		1051<br>

For each frame, the ground truth is a polygon which represents a salient closed boundary.<br>

The <xxx_TrackingGroundTruth.txt> are organized as follows:<br>
points_number x1 y1 x2 y2 x3 y3 ... ... xn yn<br>

These polyogns are annotated frame by frame manually, and they have pixel-level accuracy.<br>

If you have any problems or suggestions, feel free to contact us.<br>

The code can be found https://github.com/NathanUA/SlientClosedBoundaryTracking.<br>

Contacts
---
Xuebin Qin<br>
Department of Computing Science<br>
University of Alberta<br>
Edmonton, AB, Canada, T6G 2E8<br>

Email:<br>
xuebin@ualberta.ca<br>
xuebinua@gmail.com<br>