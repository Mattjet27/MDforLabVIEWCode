## **Relay**
### **TSM Relay Close Sessions.vi**
![alt text](/docs/images/Relay/TSM%20Relay%20Close%20Sessions.vic.png "TSM Relay Close Sessions.vi")

Use this VI to reset and close all sessions for all NI-RELAY (Switch) instruments in the Semiconductor Module Context.

![alt text](/docs/images/Relay/TSM%20Relay%20Close%20Sessions.vid.png "TSM Relay Close Sessions.vi")
### **TSM Relay Configuration Control.vi**
![alt text](/docs/images/Relay/TSM%20Relay%20Configuration%20Control.vic.png "TSM Relay Configuration Control.vi")

Performs the actions specified by the relay configuration.

![alt text](/docs/images/Relay/TSM%20Relay%20Configuration%20Control.vid.png "TSM Relay Configuration Control.vi")
### **TSM Relay Control Per-Site.vi**
![alt text](/docs/images/Relay/TSM%20Relay%20Control%20Per-Site.vic.png "TSM Relay Control Per-Site.vi")

Performs the specified per-site relay actions on all specified relays. 
-If the action array has one element the function maps it to all sites
-If the array is an even multiple size of the number of sites it maps the array multiple times (used to expand across sites)
-If the action array is not an even multiple size the function maps the array and emits a warning
-If the action array is larger than the sites it gets shortened and the function emits a warning

![alt text](/docs/images/Relay/TSM%20Relay%20Control%20Per-Site.vid.png "TSM Relay Control Per-Site.vi")
### **TSM Relay Control.vi**
![alt text](/docs/images/Relay/TSM%20Relay%20Control.vic.png "TSM Relay Control.vi")

Performs the specified relay action on all specified relays.

![alt text](/docs/images/Relay/TSM%20Relay%20Control.vid.png "TSM Relay Control.vi")
### **TSM Relay Initialize Sessions.vi**
![alt text](/docs/images/Relay/TSM%20Relay%20Initialize%20Sessions.vic.png "TSM Relay Initialize Sessions.vi")

Use this VI to initialize sessions for all  NI 2567 Relay Driver Instruments in the pin map associated with the test program. 

![alt text](/docs/images/Relay/TSM%20Relay%20Initialize%20Sessions.vid.png "TSM Relay Initialize Sessions.vi")
## **Pin Map**
### **TSM Relays to Relay Configuration.vi**
![alt text](/docs/images/Relay/TSM%20Relays%20to%20Relay%20Configuration.vic.png "TSM Relays to Relay Configuration.vi")

Populates the Relay Configuration cluster for the selected relay/action connections. This VI can be used to implement a relay configuration (set of mappings between relay(s) and positions) within a test code module.

![alt text](/docs/images/Relay/TSM%20Relays%20to%20Relay%20Configuration.vid.png "TSM Relays to Relay Configuration.vi")
### **TSM Relays to Relay Sessions.vi**
![alt text](/docs/images/Relay/TSM%20Relays%20to%20Relay%20Sessions.vic.png "TSM Relays to Relay Sessions.vi")

Populates the Relay cluster for the selected relays.

![alt text](/docs/images/Relay/TSM%20Relays%20to%20Relay%20Sessions.vid.png "TSM Relays to Relay Sessions.vi")
## **SubVIs**
### **SSC Relay Auto Expand Array to All Sessions.vim**
![alt text](/docs/images/Relay/SSC%20Relay%20Auto%20Expand%20Array%20to%20All%20Sessions.vimc.png "SSC Relay Auto Expand Array to All Sessions.vim")

This VI expands the array in to each instrument session.
Cases:
-If both arrays are empty, this function does nothing (no error)
-If the array is empty this function generates an array of default type and throws an error
-If the array has one element the function maps it to all sessions
-If the array is an even multiple size of the number of sessions it maps the array multiple times (used to expand across sites)
-If the array is not an even multiple size the function maps the array and emits a warning
-If the array is the same size as the instrument sessions it passes it straight through
-If the array is larger than the instrument sessions it gets shortened and the function and emits a warning

![alt text](/docs/images/Relay/SSC%20Relay%20Auto%20Expand%20Array%20to%20All%20Sessions.vimd.png "SSC Relay Auto Expand Array to All Sessions.vim")
