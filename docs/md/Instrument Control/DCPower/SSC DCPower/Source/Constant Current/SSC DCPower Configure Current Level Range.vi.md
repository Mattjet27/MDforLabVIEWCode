## **SSC DCPower Configure Current Level Range.vi**
### Connector Pane:
![alt text](/docs/images/Instrument%20Control/DCPower/SSC%20DCPower/Source/Constant%20Current/SSC%20DCPower%20Configure%20Current%20Level%20Range.vic.png "SSC DCPower Configure Current Level Range.vi connector pane")

### VI Description:
This VI configures the current level range. 

The range can be set when the device is in single point current mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

### Block Diagram:
![alt text](/docs/images/Instrument%20Control/DCPower/SSC%20DCPower/Source/Constant%20Current/SSC%20DCPower%20Configure%20Current%20Level%20Range.vid.png "SSC DCPower Configure Current Level Range.vi block diagram")
