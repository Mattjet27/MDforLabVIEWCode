## **SSC DCPower Configure Measurements.vi**
###Connector Pane:
![alt text](/images/DCPower/SSC%20DCPower/SSC%20DCPower%20Configure%20Measurements.vic.png "SSC DCPower Configure Measurements.vi connector pane")

###VI Description:
This VI configures the measurement mode for the sessions.

The (Auto) setting automatically chooses the optimal measurement mode individually for the instrument model in each session.

From a test time perspective Software Triggered measurements are better than using Measure Multiple, but Software Triggering isn't supported by all devices, and enabling them can make debugging in the Digital Pattern Editor more difficult.

Measure Multiple works for all devices and allows for easier debugging, but it takes longer to fetch measurements than the Software Triggered method.

###Block Diagram:
![alt text](/images/DCPower/SSC%20DCPower/SSC%20DCPower%20Configure%20Measurements.vid.png "SSC DCPower Configure Measurements.vi block diagram")
