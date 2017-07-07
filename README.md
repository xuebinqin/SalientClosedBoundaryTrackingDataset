Dataset of Salient Closed Boundary Tracking
====

This dataset contains nine video sequences captured by a webcam for salient closed boundary tracking evaluation, as shown in Fig. 1.

![Tracker_Initialization image](Tracker_Initialization.png)<br>

PARAMETERS:<br>
FPS: 30<br>
Frame size: 640(width) x 480(height)<br>
Total frames: 9598<br>

Frame numbers of each sequence: <br>
1.BookStand.avi:		899<br>
2.Bowl.avi:			1079<br>
3.GarbageBin.avi:		924<br>
4.MarkCup.avi:			859<br>
5.MarkCupContour.avi:		1226<br>
6.MarkCupPourWater.avi:		971<br>
7.NonplanarBowl.avi: 		1454<br>
8.ToolBox.avi:			1135<br>
9.TransparentCup.avi: 		1051<br>

For each frame, there are two kinds of ground truth: <br>

(1) POLYGON based ground truth in the folder "GroundTruthByPolygons".<br>
--
The <xxx_TrackingGroundTruth.txt> are organized as follows:<br>
points_number x1 y1 x2 y2 x3 y3 ... ... xn yn<br>

Xuebin Qin, Shida He, Camilo Perez Quintero, Abhineet Singh, Masood Dehghan and Martin Jagersand. "Real-time salient closed boundary tracking via line segments perceptual grouping." accepted in the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), September 2017.<br>

(2) BOUNDARY based ground truth in the folder "GroundTruthByBoundaries".<br>
--
Accurate and smooth one-pixel-width boundaries are represented by .png binary images.<br>

Xuebin Qin, Shida He, Zichen Zhang, Masood Dehghan and Martin Jagersand. "Real-time salient closed boundary tracking using perceptual grouping and shape priors." accepted in the 28th British Machine Vision Conference (BMVC), September 2017.<br>


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
