## **TSM SSC DCPower Pins to Sessions.vi**
###Connector Pane:
![alt text](/images/DCPower/TSM/TSM%20SSC%20DCPower%20Pins%20to%20Sessions.vic.png "TSM SSC DCPower Pins to Sessions.vi connector pane")

###VI Description:
Populates the TSM SSC DCPower cluster for the specified pin(s) and pin group(s). 

The "Fill SSC Pin and Site Information?" should be set to TRUE (the default value) so the DCPower SSC cluster has full information about what DCPower sessions correspond to what DUT Pins. This assists in debugging and allows for correlating arrays back to the original list of pins provided to pins to sessions.

The "Fill SSC Pin and Site Information?" input can be set to FALSE if these features aren't needed, or to optimize test time.

###Block Diagram:
![alt text](/images/DCPower/TSM/TSM%20SSC%20DCPower%20Pins%20to%20Sessions.vid.png "TSM SSC DCPower Pins to Sessions.vi block diagram")
