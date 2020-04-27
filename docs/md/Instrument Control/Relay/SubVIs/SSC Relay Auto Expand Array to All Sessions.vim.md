## **SSC Relay Auto Expand Array to All Sessions.vim**
### Connector Pane:
![alt text](/docs/images/Instrument%20Control/Relay/SubVIs/SSC%20Relay%20Auto%20Expand%20Array%20to%20All%20Sessions.vimc.png "SSC Relay Auto Expand Array to All Sessions.vim connector pane")

### VI Description:
This VI expands the array in to each instrument session.

Cases:
-If both arrays are empty, this function does nothing (no error)
-If the array is empty this function generates an array of default type and throws an error
-If the array has one element the function maps it to all sessions
-If the array is an even multiple size of the number of sessions it maps the array multiple times (used to expand across sites)
-If the array is not an even multiple size the function maps the array and emits a warning
-If the array is the same size as the instrument sessions it passes it straight through
-If the array is larger than the instrument sessions it gets shortened and the function and emits a warning

### Block Diagram:
![alt text](/docs/images/Instrument%20Control/Relay/SubVIs/SSC%20Relay%20Auto%20Expand%20Array%20to%20All%20Sessions.vimd.png "SSC Relay Auto Expand Array to All Sessions.vim block diagram")
