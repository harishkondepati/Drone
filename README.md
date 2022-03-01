# Drone
<h1>Quadcopter Using KK 2.15 Module</h1><br>
To automate drone fly, all the necessary sensors including processing power and communication chips must be built-in.<br> All these componenets are embedded in a system for better vision.With the introduction of Quadcopter, we can achieve the same efficiency as the existed commercial civilian drones with low budget so that it can be availble to the normal people.

<br>
Hardware Items:<br>

1) Quadcopter Frame (Preferrably one which has a built in Power Distribution board)<br>

2) Microcontroller (KK 2.15 Flight Controller)<br>

3) Electronic Speed Control (30 Amps) (4 pieces)<br>

4) Brushless Motor (850KV) (4 pieces)<br>

5) Propellers (2 sets)<br>

6) Power Distribution Board (Not needed if frame has a built in one)<br>

7) Lithium-Polymer 2300 mAH Battery<br>

8) FlySky FS-T6 Controller includes the Receiver<br>

9) Stress balls (4)(Extremely useful if you are a novice flyer like me)<br>



Tools and knowledge:<br>

1) Basic soldering skills<br>
2) Alan keys<br>
3) Shrink tubes(Preferably Turnigy)<br>
4) Zip ties (To hold the ESC's onto the frame)<br>
5) Glue gun (To put all over the connections to avoid any contact between them)<br>

Step 2: Assemble and Connect<br>
Assemble and Connect<br>
1) The motors and ESC's can be connected to each other via direct soldering or using Bullet Connectors of 4mm dimension.<br>

2) The ESC's are then connected to the power distribution board, or in this case directly to the frame which has an inbuilt power distribution board, by soldering. (Make sure to know if the ESC's are supposed to be flashed or not, mine did not required to do so.)

<br>3) Once this is done, solder the battery wire to the frame.<br>

4) Once all the soldering work is done,and the hardware is setup, connect the KK Board(again flashed with the latest firmware) with the ESC servo wires, and Receiver.
<br>
Add TipAsk QuestionCommentDownload<br>
Step 3: Plug in the Battery and Test Your Quadcopter<br>
Plug in the Battery and Test Your Quadcopter<br>
1) If your code is all correct and your connections are all good you should see the LCD screen on the board lit up, from where you can easily calibrate both the Accelerometer and Magnetometer.
<br>
Exact steps to be followed for the setup<br>
2) Connect the controller to your laptop and download the T6Config application on to your desktop and test the controls to see if the Throttle, Pitch, Yaw and Altitude are not inverted.
<br>
3) Set End points to 100% and subtrim each channel according to your needs and quad's stability.<br>
4) Now arm the KK Board(you'd see ARMED come up on the LCD screen) and gradually increase the throttle. If everything is perfecty connected, flashed and calibrated the motors will start rotating.
<br>
I attached the Stress balls, to ensure in the event of I having to cut the throttle at any instant, the landing wouldn't destroy any of the parts or the frame.
<br>
While this whole task took me 2 days, there is still room for improvements like controlling the quadcopter with a mobile device rather than a remote.
<br>
When I will upgrade my quadcopter with FPV (first-person view), i.e. equip my quadcopter with a camera, video transmitter, video receiver and goggles/monitor to have a live video feed down to the ground, which will also mean purchasing a battery of much higher capacity than the present one.<br>
