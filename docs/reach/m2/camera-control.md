Reach M2 is able to trigger cameras as well as register events. Event mark feature is a must for aerial mapping as it allows to register precise time when shutter was activated.

<p style="text-align:center" ><img src="../img/reachm2/camera-control/camera-control-settings.png" style="width: 800px;" /></p>

### Camera trigger
By altering the duty cycle and period parameters you can match settings required for triggering your camera module. Real-time signal graph is shown on the same page. Note, that this feature does not have to be used if your autopilot is able to trigger the camera, as it has more information about the flight plan and can make more informed decisions on when to fire the camera. 

### Camera events
You see the time of the last event for real-time debugging. Only works with GNSS satellites in view for time synchronization. An event is triggered by driving time mark pin down, usually by a camera hot shoe. It is possible to connect Reach M2 with an adapter to any camera with hot shoe (e.g. Sony, Canon, Nikon). All event marks are stored in the raw data log. Time mark pin is designed to be directly connected to a hot shoe cable without any additional electronic parts such as resistors or capacitors.

#### Connecting Reach M2 to a camera using HSA

To connect Reach M2 to a camera with hot shoe adapter (HSA) use 5-pin JST-GH cable. Attach JST-GH connector to С1 port on Reach M2. Make sure you connect the adapter to a hot shoe of a camera correctly:

<p style="text-align:center" ><img src="../img/reachm2/camera-control/hot-shoe-connection.jpg" style="width: 500px;" /></p>
