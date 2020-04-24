## **DCPower**
### **TSM SSC DCPower Configure Measurements.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Measurements.vic.png "TSM SSC DCPower Configure Measurements.vi")

This VI configures the measurement mode for the sessions.
The (Auto) setting automatically chooses the optimal measurement mode individually for the instrument model in each session.
From a test time perspective Software Triggered measurements are better than using Measure Multiple, but Software Triggering isn't supported by all devices, and enabling them can make debugging in the Digital Pattern Editor more difficult.
Measure Multiple works for all devices and allows for easier debugging, but it takes longer to fetch measurements than the Software Triggered method.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Measurements.vid.png "TSM SSC DCPower Configure Measurements.vi")
### **TSM SSC DCPower Configure Settings.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Settings.vimc.png "TSM SSC DCPower Configure Settings.vim")

This VI configures important DCPower channel settings for the sessions.
Settings are ignored if they aren't supported by the devices being used.
Note inputs are recommended, and each can be single elements or arrays.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Settings.vimd.png "TSM SSC DCPower Configure Settings.vim")
### **TSM SSC DCPower Force Current Asymmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Current%20Asymmetric%20Limits.vimc.png "TSM SSC DCPower Force Current Asymmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Current%20Asymmetric%20Limits.vimd.png "TSM SSC DCPower Force Current Asymmetric Limits.vim")
### **TSM SSC DCPower Force Current Symmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Current%20Symmetric%20Limits.vimc.png "TSM SSC DCPower Force Current Symmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Current%20Symmetric%20Limits.vimd.png "TSM SSC DCPower Force Current Symmetric Limits.vim")
### **TSM SSC DCPower Force Voltage Asymmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Voltage%20Asymmetric%20Limits.vimc.png "TSM SSC DCPower Force Voltage Asymmetric Limits.vim")

This VI forces voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Voltage%20Asymmetric%20Limits.vimd.png "TSM SSC DCPower Force Voltage Asymmetric Limits.vim")
### **TSM SSC DCPower Force Voltage Symmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Voltage%20Symmetric%20Limits.vimc.png "TSM SSC DCPower Force Voltage Symmetric Limits.vim")

This VI fources voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Force%20Voltage%20Symmetric%20Limits.vimd.png "TSM SSC DCPower Force Voltage Symmetric Limits.vim")
### **TSM SSC DCPower Measure.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Measure.vic.png "TSM SSC DCPower Measure.vi")

This VI takes a Voltage and Current measurement for each session.
Measurement Mode is a recommended input. The Auto setting will check the measurement mode for each session and use the appropriate measurement method per session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Measure.vid.png "TSM SSC DCPower Measure.vi")
## **Control**
### **TSM SSC DCPower Abort.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Abort.vic.png "TSM SSC DCPower Abort.vi")

Transitions the NI-DCPower sessions from the Running state to the Committed state. If a sequence is running, it is stopped.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Abort.vid.png "TSM SSC DCPower Abort.vi")
### **TSM SSC DCPower Commit.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Commit.vic.png "TSM SSC DCPower Commit.vi")

Applies previously configured settings to the device. Calling this VI moves the NI-DCPower sessions from the Uncommitted state into the Committed state.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Commit.vid.png "TSM SSC DCPower Commit.vi")
### **TSM SSC DCPower Initiate.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Initiate.vic.png "TSM SSC DCPower Initiate.vi")

Starts generation or acquisition, causing the NI-DCPower sessions to leave the Uncommitted state or Committed state and enter the Running state.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Initiate.vid.png "TSM SSC DCPower Initiate.vi")
### **TSM SSC DCPower Reset Channels.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Reset%20Channels.vic.png "TSM SSC DCPower Reset Channels.vi")

Resets the device to a known state. This VI disables power generation, resets session properties to their default values, commits the session properties, and leaves the sessions in the Uncommitted state. You can use this VI to clear certain errors in less time than using niDCPower Reset Device VI. Refer to the Programming States topic in the NI DC Power Supplies and SMUs Help for more information about NI-DCPower software states.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Reset%20Channels.vid.png "TSM SSC DCPower Reset Channels.vi")
## **Query**
### **TSM SSC DCPower Query In Compliance.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Query%20In%20Compliance.vic.png "TSM SSC DCPower Query In Compliance.vi")

Queries the specified output channels to determine if they is operating at the compliance limits.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Query%20In%20Compliance.vid.png "TSM SSC DCPower Query In Compliance.vi")
### **TSM SSC DCPower Query Output State.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Query%20Output%20State.vic.png "TSM SSC DCPower Query Output State.vi")

Queries the specified output channel to determine if the output channels are currently in the state specified by <B>output state</B>.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Query%20Output%20State.vid.png "TSM SSC DCPower Query Output State.vi")
## **Source**
### **TSM SSC DCPower Configure Output Connected.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Connected.vic.png "TSM SSC DCPower Configure Output Connected.vi")

This VI configures output enabled on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Connected.vid.png "TSM SSC DCPower Configure Output Connected.vi")
### **TSM SSC DCPower Configure Output Enabled And Connected.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Enabled%20And%20Connected.vic.png "TSM SSC DCPower Configure Output Enabled And Connected.vi")

This VI configures output enabled and connected on the channels.
T - Enable and then connect
F - Disconnect and then disable

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Enabled%20And%20Connected.vid.png "TSM SSC DCPower Configure Output Enabled And Connected.vi")
### **TSM SSC DCPower Configure Output Enabled.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Enabled.vic.png "TSM SSC DCPower Configure Output Enabled.vi")

This VI configures output enabled on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Enabled.vid.png "TSM SSC DCPower Configure Output Enabled.vi")
### **TSM SSC DCPower Configure Output Resistance.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Resistance.vic.png "TSM SSC DCPower Configure Output Resistance.vi")

This VI configures output resistance on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Output%20Resistance.vid.png "TSM SSC DCPower Configure Output Resistance.vi")
### **TSM SSC DCPower Configure Source Delay.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Source%20Delay.vic.png "TSM SSC DCPower Configure Source Delay.vi")

This VI configures the Source Delay.
This can be used when in the single point mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Source%20Delay.vid.png "TSM SSC DCPower Configure Source Delay.vi")
### **TSM SSC DCPower Get Max Current.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Get%20Max%20Current.vic.png "TSM SSC DCPower Get Max Current.vi")

This VI returns the max Current (A) Range for each DCPower Session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Get%20Max%20Current.vid.png "TSM SSC DCPower Get Max Current.vi")
## **Source\Source Adapt**
### **TSM SSC DCPower Configure Transient Response.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Transient%20Response.vic.png "TSM SSC DCPower Configure Transient Response.vi")

This VI configures the transient response setting for the channel.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20Transient%20Response.vid.png "TSM SSC DCPower Configure Transient Response.vi")
## **SubVIs**
### **TSM DCPower Expand Array to Sessions.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Expand%20Array%20to%20Sessions.vimc.png "TSM DCPower Expand Array to Sessions.vim")



![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Expand%20Array%20to%20Sessions.vimd.png "TSM DCPower Expand Array to Sessions.vim")
### **TSM SSC DCPower Expanded Pin List to DCPower SSC Order.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Expanded%20Pin%20List%20to%20DCPower%20SSC%20Order.vic.png "TSM SSC DCPower Expanded Pin List to DCPower SSC Order.vi")



![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Expanded%20Pin%20List%20to%20DCPower%20SSC%20Order.vid.png "TSM SSC DCPower Expanded Pin List to DCPower SSC Order.vi")
## **Triggers and Events**
### **TSM SSC DCPower Wait for Event.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Wait%20for%20Event.vic.png "TSM SSC DCPower Wait for Event.vi")

This VI waits until the devices have generated the specified event.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Wait%20for%20Event.vid.png "TSM SSC DCPower Wait for Event.vi")
## **TSM**
### **SSC DCPower Filter Pins.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/SSC%20DCPower%20Filter%20Pins.vic.png "SSC DCPower Filter Pins.vi")

This VI filters the TSM SSC cluster to requested pins.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/SSC%20DCPower%20Filter%20Pins.vid.png "SSC DCPower Filter Pins.vi")
### **SSC DCPower Filter Sites.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/SSC%20DCPower%20Filter%20Sites.vic.png "SSC DCPower Filter Sites.vi")

This VI filters the SSC array to requested sites.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/SSC%20DCPower%20Filter%20Sites.vid.png "SSC DCPower Filter Sites.vi")
### **TSM DCPower Close Sessions.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Close%20Sessions.vic.png "TSM DCPower Close Sessions.vi")



![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Close%20Sessions.vid.png "TSM DCPower Close Sessions.vi")
### **TSM DCPower Initialize Sessions.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Initialize%20Sessions.vic.png "TSM DCPower Initialize Sessions.vi")



![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20DCPower%20Initialize%20Sessions.vid.png "TSM DCPower Initialize Sessions.vi")
### **TSM SSC DCPower Filter Pins.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Filter%20Pins.vic.png "TSM SSC DCPower Filter Pins.vi")

This VI filters the TSM SSC cluster to requested pins.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Filter%20Pins.vid.png "TSM SSC DCPower Filter Pins.vi")
### **TSM SSC DCPower Filter Sites.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Filter%20Sites.vic.png "TSM SSC DCPower Filter Sites.vi")

This VI filters the TSM SSC cluster to requested sites.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Filter%20Sites.vid.png "TSM SSC DCPower Filter Sites.vi")
### **TSM SSC DCPower Pins to Sessions.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Pins%20to%20Sessions.vic.png "TSM SSC DCPower Pins to Sessions.vi")

Populates the TSM SSC DCPower cluster for the specified pin(s) and pin group(s). 
The "Fill SSC Pin and Site Information?" should be set to TRUE (the default value) so the DCPower SSC cluster has full information about what DCPower sessions correspond to what DUT Pins. This assists in debugging and allows for correlating arrays back to the original list of pins provided to pins to sessions.
The "Fill SSC Pin and Site Information?" input can be set to FALSE if these features aren't needed, or to optimize test time.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Pins%20to%20Sessions.vid.png "TSM SSC DCPower Pins to Sessions.vi")
## **Waveform Acquisition**
### **TSM SSC DCPower Configure and Start Waveform Acquisition.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20and%20Start%20Waveform%20Acquisition.vic.png "TSM SSC DCPower Configure and Start Waveform Acquisition.vi")

This VI aborts the task, configures the tasks for waveform acquisition, initializes the task and starts the acquisition.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Configure%20and%20Start%20Waveform%20Acquisition.vid.png "TSM SSC DCPower Configure and Start Waveform Acquisition.vi")
### **TSM SSC DCPower Finish Waveform Acquisition.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Finish%20Waveform%20Acquisition.vic.png "TSM SSC DCPower Finish Waveform Acquisition.vi")

This VI reconfigures the SMU to the previous settings and outputs the samples captured during waveform acquisition.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/TSM%20SSC%20DCPower%20Finish%20Waveform%20Acquisition.vid.png "TSM SSC DCPower Finish Waveform Acquisition.vi")
