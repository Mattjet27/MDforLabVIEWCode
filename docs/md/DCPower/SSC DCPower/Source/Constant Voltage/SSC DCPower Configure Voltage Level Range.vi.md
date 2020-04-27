## **SSC DCPower Configure Voltage Level Range.vi**
###Connector Pane:
![alt text](/SSC%20DCPower/Source/Constant%20Voltage/SSC%20DCPower%20Configure%20Voltage%20Level%20Range.vic.png "SSC DCPower Configure Voltage Level Range.vi connector pane")

###VI Description:
This VI configures the voltage level range. 

The range can be set when the device is in single point voltage mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

###Block Diagram:
![alt text](/SSC%20DCPower/Source/Constant%20Voltage/SSC%20DCPower%20Configure%20Voltage%20Level%20Range.vid.png "SSC DCPower Configure Voltage Level Range.vi block diagram")
