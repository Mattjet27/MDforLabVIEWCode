## **TSM Relay Control Per-Site.vi**
### Connector Pane:
![alt text](/images/Instrument%20Control/Relay/TSM%20Relay%20Control%20Per-Site.vic.png "TSM Relay Control Per-Site.vi connector pane")

### VI Description:
Performs the specified per-site relay actions on all specified relays. 

-If the action array has one element the function maps it to all sites
-If the array is an even multiple size of the number of sites it maps the array multiple times (used to expand across sites)
-If the action array is not an even multiple size the function maps the array and emits a warning
-If the action array is larger than the sites it gets shortened and the function emits a warning

### Block Diagram:
![alt text](/images/Instrument%20Control/Relay/TSM%20Relay%20Control%20Per-Site.vid.png "TSM Relay Control Per-Site.vi block diagram")
