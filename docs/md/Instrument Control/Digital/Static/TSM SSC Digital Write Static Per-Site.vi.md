## **TSM SSC Digital Write Static Per-Site.vi**
### Connector Pane:
![alt text](/docs/images/Instrument%20Control/Digital/Static/TSM%20SSC%20Digital%20Write%20Static%20Per-Site.vic.png "TSM SSC Digital Write Static Per-Site.vi connector pane")

### VI Description:
Writes per-site static states to the specified pin(s) and pin group(s). The selected pins remain in the specified state until the next pattern burst or call to this VI. If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins.

This VI does not change the selected pin function. If you write a static state to a pin that does not have the Digital function selected, the new static state is stored by the digital pattern instrument, and affects the state of the pin the next time you change the selected function to Digital.

### Block Diagram:
![alt text](/docs/images/Instrument%20Control/Digital/Static/TSM%20SSC%20Digital%20Write%20Static%20Per-Site.vid.png "TSM SSC Digital Write Static Per-Site.vi block diagram")
