## **SSC Digital Write Static.vi**
###Connector Pane:
![alt text](/Digital/SSC%20Digital/Static/SSC%20Digital%20Write%20Static.vic.png "SSC Digital Write Static.vi connector pane")

###VI Description:
Writes a static state to all specified pin(s) and pin group(s). The selected pins remain in the specified state until the next pattern burst or call to this VI. If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins.

This VI does not change the selected pin function. If you write a static state to a pin that does not have the Digital function selected, the new static state is stored by the digital pattern instrument, and affects the state of the pin the next time you change the selected function to Digital.


###Block Diagram:
![alt text](/Digital/SSC%20Digital/Static/SSC%20Digital%20Write%20Static.vid.png "SSC Digital Write Static.vi block diagram")
