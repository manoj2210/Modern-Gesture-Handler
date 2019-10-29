# Modern-Gesture-Handler

<h4>A modern gesture handler for laptops and PC done with Arduino and Ultra Sonic Sensor</h4>

<img src="img.jpg" width=400 height=250/>

<p>This sensor can detect the distance of the obstacle.<br> Making use of this sensor we can define different gestures which can further be converted into mathematical equations, then send it to the computer to do specific tasks</p>

<h3>Should the arduino and the sensor run all the time?</h3>
<p>The answer is no, they need not run all the time. The sensor can transmit the data to the computer only when the obstacle or the hand gesture is nearer or below threshold distance.<br>
To find the threshold we define a starting time of 2 seconds for the sensor to find the threshold distance.
It gets the data and finds the median due to the reason, some error might occur.
</p>

<h3>How the gesture is identified?</h3>
<p>When the obstacle occurs in the threshold distance, the arduino transmits the data to the computer. The computer then processes the data using regression to find the correct mathematical equation and performs the task associated with it.</p>

<h3>How many gestures are possible with it?</h3>
<p>There can be 3 gestures on one sensor(slope positive 1, slope negative 1 and slope 0). So making it 6 on two sensors separately. There can be 5 more (left and right slope +ve, -ve, constant,left +ve and right -ve,right +ve and left -ve). Thus there can be 11 different gestures for a single currently running application</p>

<p>These gestures are defined for differnt applications and some can also be globally defined. </p>

