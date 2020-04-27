## **TSM SSC Digital N Pins To M Sessions.vi**
###Connector Pane:
![alt text](/Instrument%20Control/Digital/TSM/TSM%20SSC%20Digital%20N%20Pins%20To%20M%20Sessions.vic.png "TSM SSC Digital N Pins To M Sessions.vi connector pane")

###VI Description:
Populates the TSM SSC Digital cluster for the specified pin(s) and pin group(s). 

The "Turn Pin Groups to Pins?" should be set to TRUE when using pin groups, since it's important for the TSM SSC functions to have a full list of DUT pins when mapping instrument indexed results into per-site per-pin results.

The "Turn Pin Groups to Pins?" input can be set to FALSE <b>if the Pins input doesn't contain any pin groups</b>. This setting is preferred when optimizing test time.

###Block Diagram:
![alt text](/Instrument%20Control/Digital/TSM/TSM%20SSC%20Digital%20N%20Pins%20To%20M%20Sessions.vid.png "TSM SSC Digital N Pins To M Sessions.vi block diagram")
