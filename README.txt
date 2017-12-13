The robot grid class makes a pathable series of points based on the feild being a cordinate grid 
The consturctor has 4 peramiters the first perameter is the starting x cordiante of the robot the second perameter is the starting y cordinate the third peramater is the starting angle of a spline the last perameter is the precision of your spline in points per degree
the x cordinate is the distance from the driver station
the y cordiante is the distance from the left side wall
the y cordinate is less then the previous one for a left spline the y cordinate is greater then the previous for a right spline
if you want to path a straight line you use the addLinearPoint method 
this method has 3 perameters the first being a x cordinate which is its target x value the second being a y cordinate which is the target y value and the last being angle which is the angle of the robot
if you want to path an arc you use the addPoint method this method also has 3 parameters the first two are the same as the addLinearPoint the last on is angle which is the angle you want he robot to end at
the getAngle method is to get the angle to robot is supposed to be heading it has one perameter which is distance which is the average between the distance traveled by both sides of the robot
the getReverseAngle method behaves the same and has the same perameters as the getAngle method but is the robots heading for following backwards
