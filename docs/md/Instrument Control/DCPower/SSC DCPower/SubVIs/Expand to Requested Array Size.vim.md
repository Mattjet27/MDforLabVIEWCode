## **Expand to Requested Array Size.vim**
### Connector Pane:
![alt text](/DCPower/SSC%20DCPower/SubVIs/Expand%20to%20Requested%20Array%20Size.vimc.png "Expand to Requested Array Size.vim connector pane")

### VI Description:
This VI expands the array in to the requested size.

Cases:
-If both sizes are zero, this function does nothing (no error)
-If the array is empty this function generates an array of default type and throws an error
-If the array has one element the function maps it to the requested size
-If the array is an even multiple size of the requested size it maps the array multiple times (used to expand across sites)
-If the array is not an even multiple size the function maps the array and throws a warning
-If the array is the same size as the requested size it passes it straight through
-If the array is larger than the instrument sessions it gets shortened and a warning is emitted

### Block Diagram:
![alt text](/DCPower/SSC%20DCPower/SubVIs/Expand%20to%20Requested%20Array%20Size.vimd.png "Expand to Requested Array Size.vim block diagram")
