## **SSC DCPower**
### **SSC DCPower Configure Measurements.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Measurements.vic.png "SSC DCPower Configure Measurements.vi")

This VI configures the measurement mode for the sessions.
The (Auto) setting automatically chooses the optimal measurement mode individually for the instrument model in each session.
From a test time perspective Software Triggered measurements are better than using Measure Multiple, but Software Triggering isn't supported by all devices, and enabling them can make debugging in the Digital Pattern Editor more difficult.
Measure Multiple works for all devices and allows for easier debugging, but it takes longer to fetch measurements than the Software Triggered method.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Measurements.vid.png "SSC DCPower Configure Measurements.vi")
### **SSC DCPower Configure Settings.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Settings.vimc.png "SSC DCPower Configure Settings.vim")

This VI configures important DCPower channel settings for the sessions.
Settings are ignored if they aren't supported by the devices being used.
Note inputs are recommended, and each can be single elements or arrays.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Settings.vimd.png "SSC DCPower Configure Settings.vim")
### **SSC DCPower Force Current Asymmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Asymmetric Limits.vimc.png "SSC DCPower Force Current Asymmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Asymmetric Limits.vimd.png "SSC DCPower Force Current Asymmetric Limits.vim")
### **SSC DCPower Force Current Symmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Symmetric Limits.vimc.png "SSC DCPower Force Current Symmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Symmetric Limits.vimd.png "SSC DCPower Force Current Symmetric Limits.vim")
### **SSC DCPower Force Voltage Asymmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Asymmetric Limits.vimc.png "SSC DCPower Force Voltage Asymmetric Limits.vim")

This VI forces voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Asymmetric Limits.vimd.png "SSC DCPower Force Voltage Asymmetric Limits.vim")
### **SSC DCPower Force Voltage Symmetric Limits.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Symmetric Limits.vimc.png "SSC DCPower Force Voltage Symmetric Limits.vim")

This VI forces voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Symmetric Limits.vimd.png "SSC DCPower Force Voltage Symmetric Limits.vim")
### **SSC DCPower Measure.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Measure.vic.png "SSC DCPower Measure.vi")

This VI takes a Voltage and Current measurement for each session.
Measurement Mode is a recommended input. The Auto setting will check the measurement mode for each session and use the appropriate measurement method per session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Measure.vid.png "SSC DCPower Measure.vi")
## **SSC DCPower\Control**
### **SSC DCPower Abort.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Abort.vic.png "SSC DCPower Abort.vi")

Transitions the NI-DCPower sessions from the Running state to the Committed state. If a sequence is running, it is stopped.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Abort.vid.png "SSC DCPower Abort.vi")
### **SSC DCPower Commit.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Commit.vic.png "SSC DCPower Commit.vi")

Applies previously configured settings to the device. Calling this VI moves the NI-DCPower sessions from the Uncommitted state into the Committed state.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Commit.vid.png "SSC DCPower Commit.vi")
### **SSC DCPower Initiate.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Initiate.vic.png "SSC DCPower Initiate.vi")

Starts generation or acquisition, causing the NI-DCPower sessions to leave the Uncommitted state or Committed state and enter the Running state.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Initiate.vid.png "SSC DCPower Initiate.vi")
### **SSC DCPower Reset Channels.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Reset Channels.vic.png "SSC DCPower Reset Channels.vi")

Resets the device to a known state. This VI disables power generation, resets session properties to their default values, commits the session properties, and leaves the sessions in the Uncommitted state. You can use this VI to clear certain errors in less time than using niDCPower Reset Device VI. Refer to the Programming States topic in the NI DC Power Supplies and SMUs Help for more information about NI-DCPower software states.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Reset Channels.vid.png "SSC DCPower Reset Channels.vi")
## **SSC DCPower\Measure**
### **Single SSC DCPower Configure Settings.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Settings.vic.png "Single SSC DCPower Configure Settings.vi")

This VI configures important DCPower channel settings for a session.
Settings are ignored if they aren't supported by the device being used.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Settings.vid.png "Single SSC DCPower Configure Settings.vi")
### **Single SSC DCPower Get Aperture Times in Seconds.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Get Aperture Times in Seconds.vic.png "Single SSC DCPower Get Aperture Times in Seconds.vi")

This VI gets the measurement aperture time of the session in seconds (if it was set in units of PLCs, it converts it to seconds).

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Get Aperture Times in Seconds.vid.png "Single SSC DCPower Get Aperture Times in Seconds.vi")
### **SSC DCPower Configure Aperture Time with Abort and Initiate.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Aperture Time with Abort and Initiate.vic.png "SSC DCPower Configure Aperture Time with Abort and Initiate.vi")

This VI aborts, configures measurement aperture time, and initializes the sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Aperture Time with Abort and Initiate.vid.png "SSC DCPower Configure Aperture Time with Abort and Initiate.vi")
### **SSC DCPower Configure Aperture Time.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Aperture Time.vic.png "SSC DCPower Configure Aperture Time.vi")

This VI configures measurement aperture time of the sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Aperture Time.vid.png "SSC DCPower Configure Aperture Time.vi")
### **SSC DCPower Configure Power Line Frequency.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Power Line Frequency.vic.png "SSC DCPower Configure Power Line Frequency.vi")

This VI configures the power line frequency of the sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Power Line Frequency.vid.png "SSC DCPower Configure Power Line Frequency.vi")
### **SSC DCPower Configure Sense.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Sense.vic.png "SSC DCPower Configure Sense.vi")

This VI configures local or remote sense for the sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Sense.vid.png "SSC DCPower Configure Sense.vi")
### **SSC DCPower Configure Settings Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Settings Array.vic.png "SSC DCPower Configure Settings Array.vi")

This VI configures important DCPower channel settings for the sessions.
Settings are ignored if they aren't supported by the device being used.
Note all inputs are required, and all need to be populated with values for every session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Settings Array.vid.png "SSC DCPower Configure Settings Array.vi")
### **SSC DCPower Debug Global.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Debug Global.vic.png "SSC DCPower Debug Global.vi")



![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Debug Global.vid.png "SSC DCPower Debug Global.vi")
### **SSC DCPower Get Aperture Times in Seconds.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Aperture Times in Seconds.vic.png "SSC DCPower Get Aperture Times in Seconds.vi")

This VI gets the measurement aperture time of the sessions in seconds (if it was set in units of PLCs, it converts it to seconds).

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Aperture Times in Seconds.vid.png "SSC DCPower Get Aperture Times in Seconds.vi")
### **SSC DCPower Get Power Line Frequencies.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Power Line Frequencies.vic.png "SSC DCPower Get Power Line Frequencies.vi")

This VI gets the configured power line frequency for the sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Power Line Frequencies.vid.png "SSC DCPower Get Power Line Frequencies.vi")
## **SSC DCPower\Query**
### **SSC DCPower Query In Compliance.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Query In Compliance.vic.png "SSC DCPower Query In Compliance.vi")

Queries the specified output channels to determine if they is operating at the compliance limits.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Query In Compliance.vid.png "SSC DCPower Query In Compliance.vi")
### **SSC DCPower Query Output State.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Query Output State.vic.png "SSC DCPower Query Output State.vi")

Queries the specified output channel to determine if the output channels are currently in the state specified by <B>output state</B>.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Query Output State.vid.png "SSC DCPower Query Output State.vi")
## **SSC DCPower\Source**
### **SSC DCPower Configure Output Connected.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Connected.vic.png "SSC DCPower Configure Output Connected.vi")

This VI configures output enabled on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Connected.vid.png "SSC DCPower Configure Output Connected.vi")
### **SSC DCPower Configure Output Enabled And Connected.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Enabled And Connected.vic.png "SSC DCPower Configure Output Enabled And Connected.vi")

This VI configures output enabled and connected on the channels.
T - Enable and then connect
F - Disconnect and then disable

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Enabled And Connected.vid.png "SSC DCPower Configure Output Enabled And Connected.vi")
### **SSC DCPower Configure Output Enabled.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Enabled.vic.png "SSC DCPower Configure Output Enabled.vi")

This VI configures output enabled on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Enabled.vid.png "SSC DCPower Configure Output Enabled.vi")
### **SSC DCPower Configure Output Function.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Function.vic.png "SSC DCPower Configure Output Function.vi")

This VI configures the output function of the instrument sessions. The tasks must be aborted when calling this method.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Function.vid.png "SSC DCPower Configure Output Function.vi")
### **SSC DCPower Configure Output Resistance Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Resistance Array.vic.png "SSC DCPower Configure Output Resistance Array.vi")

This VI configures output resistance on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Resistance Array.vid.png "SSC DCPower Configure Output Resistance Array.vi")
### **SSC DCPower Configure Output Resistance.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Resistance.vic.png "SSC DCPower Configure Output Resistance.vi")

This VI configures output resistance on the channels.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Output Resistance.vid.png "SSC DCPower Configure Output Resistance.vi")
### **SSC DCPower Configure Source Delay.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Delay.vic.png "SSC DCPower Configure Source Delay.vi")

This VI configures the Source Delay.
This can be used when in the single point mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Delay.vid.png "SSC DCPower Configure Source Delay.vi")
### **SSC DCPower Configure Source Mode.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Mode.vic.png "SSC DCPower Configure Source Mode.vi")

This VI configures the sourcing mode of the instrument sessions. The tasks must be aborted when calling this method.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Mode.vid.png "SSC DCPower Configure Source Mode.vi")
### **SSC DCPower Get Max Current.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Max Current.vic.png "SSC DCPower Get Max Current.vi")

This VI returns the max Current (A) Range for each DCPower Session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Max Current.vid.png "SSC DCPower Get Max Current.vi")
## **SSC DCPower\Source\Constant Current**
### **Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi")

This VI configures the sessions to force a single point DC current level with asymmetic voltage limits.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi")
### **Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi")

This VI configures the sessions to force a single point DC current level with a voltage limit.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi")
### **SSC DCPower Configure Current Level Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level Array.vic.png "SSC DCPower Configure Current Level Array.vi")

This VI configures the Current Level with an array input. This properly expands the array as needed to apply to all sessions.
This can be used when in the single point current mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level Array.vid.png "SSC DCPower Configure Current Level Array.vi")
### **SSC DCPower Configure Current Level Range.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level Range.vic.png "SSC DCPower Configure Current Level Range.vi")

This VI configures the current level range. 
The range can be set when the device is in single point current mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level Range.vid.png "SSC DCPower Configure Current Level Range.vi")
### **SSC DCPower Configure Current Level.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level.vic.png "SSC DCPower Configure Current Level.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Level.vid.png "SSC DCPower Configure Current Level.vi")
### **SSC DCPower Configure Voltage Limit Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit Array.vic.png "SSC DCPower Configure Voltage Limit Array.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit Array.vid.png "SSC DCPower Configure Voltage Limit Array.vi")
### **SSC DCPower Configure Voltage Limit Range.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit Range.vic.png "SSC DCPower Configure Voltage Limit Range.vi")

This VI configures the voltage limit range. 
The range can be set when the device is in single point current mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit Range.vid.png "SSC DCPower Configure Voltage Limit Range.vi")
### **SSC DCPower Configure Voltage Limit.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit.vic.png "SSC DCPower Configure Voltage Limit.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Limit.vid.png "SSC DCPower Configure Voltage Limit.vi")
### **SSC DCPower Force Current Array Asymmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Array Asymmetric Limits.vic.png "SSC DCPower Force Current Array Asymmetric Limits.vi")

This VI sources current on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Array Asymmetric Limits.vid.png "SSC DCPower Force Current Array Asymmetric Limits.vi")
### **SSC DCPower Force Current Array Symmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Array Symmetric Limits.vic.png "SSC DCPower Force Current Array Symmetric Limits.vi")

This VI forces current on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Current Array Symmetric Limits.vid.png "SSC DCPower Force Current Array Symmetric Limits.vi")
## **SSC DCPower\Source\Constant Voltage**
### **Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi")

This VI configures the instrument sessions to force a single voltage with asymmetric current limits.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi")
### **Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi")

This VI configures the instrument sessions to force a single voltage.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi")
### **SSC DCPower Configure Current Limit Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit Array.vic.png "SSC DCPower Configure Current Limit Array.vi")

This VI configures the Current Limit.
This can be used when in the single point voltage mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit Array.vid.png "SSC DCPower Configure Current Limit Array.vi")
### **SSC DCPower Configure Current Limit Range.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit Range.vic.png "SSC DCPower Configure Current Limit Range.vi")

This VI configures the current limit range. 
The range can be set when the device is in single point voltage mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit Range.vid.png "SSC DCPower Configure Current Limit Range.vi")
### **SSC DCPower Configure Current Limit.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit.vic.png "SSC DCPower Configure Current Limit.vi")

This VI configures the Current Limit.
This can be used when in the single point voltage mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Current Limit.vid.png "SSC DCPower Configure Current Limit.vi")
### **SSC DCPower Configure Voltage Level Array.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level Array.vic.png "SSC DCPower Configure Voltage Level Array.vi")

This VI configures the Voltage Level with an array input. This properly expands the array as needed to apply to all sessions.
This can be used when in the single point voltage mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level Array.vid.png "SSC DCPower Configure Voltage Level Array.vi")
### **SSC DCPower Configure Voltage Level Range.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level Range.vic.png "SSC DCPower Configure Voltage Level Range.vi")

This VI configures the voltage level range. 
The range can be set when the device is in single point voltage mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level Range.vid.png "SSC DCPower Configure Voltage Level Range.vi")
### **SSC DCPower Configure Voltage Level.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level.vic.png "SSC DCPower Configure Voltage Level.vi")

This VI configures the Voltage Level.
This can be used when in the single point voltage mode.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Voltage Level.vid.png "SSC DCPower Configure Voltage Level.vi")
### **SSC DCPower Force Voltage Array Asymmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Array Asymmetric Limits.vic.png "SSC DCPower Force Voltage Array Asymmetric Limits.vi")

This VI forces voltage on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Array Asymmetric Limits.vid.png "SSC DCPower Force Voltage Array Asymmetric Limits.vi")
### **SSC DCPower Force Voltage Array Symmetric Limits.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Array Symmetric Limits.vic.png "SSC DCPower Force Voltage Array Symmetric Limits.vi")

This VI forces voltage on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Force Voltage Array Symmetric Limits.vid.png "SSC DCPower Force Voltage Array Symmetric Limits.vi")
## **SSC DCPower\Source\Source Adapt**
### **SSC DCPower Configure Source Adapt.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Adapt.vic.png "SSC DCPower Configure Source Adapt.vi")

This VI configures Source Adapt parameters for the channels and sets them to the Custom transient response setting.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Source Adapt.vid.png "SSC DCPower Configure Source Adapt.vi")
### **SSC DCPower Configure Transient Response.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Transient Response.vic.png "SSC DCPower Configure Transient Response.vi")

This VI configures the transient response setting for the channel.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure Transient Response.vid.png "SSC DCPower Configure Transient Response.vi")
### **SSC DCPower Get Source Adapt Settings.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Source Adapt Settings.vic.png "SSC DCPower Get Source Adapt Settings.vi")

This VI gets the transient response settings (e.g. Source Adapt parameters) for the channels.
This can be used to get the source adapt parameters for the default transient response settings (Slow, Normal, Fast) if the channels are in those modes.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get Source Adapt Settings.vid.png "SSC DCPower Get Source Adapt Settings.vi")
## **SSC DCPower\SubVIs**
### **DCPower Model to Ranges.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/DCPower Model to Ranges.vic.png "DCPower Model to Ranges.vi")

This VI takes a DCPower Model Number (such as "4139") and outupts it's Voltage, Current, and Output Resistance (if supported) ranges.
For devices that don't support Output Resistance, the array returned will be empty for the ranges.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/DCPower Model to Ranges.vid.png "DCPower Model to Ranges.vi")
### **Expand to Requested Array Size.vim**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Expand to Requested Array Size.vimc.png "Expand to Requested Array Size.vim")

This VI expands the array in to the requested size.
Cases:
-If both sizes are zero, this function does nothing (no error)
-If the array is empty this function generates an array of default type and throws an error
-If the array has one element the function maps it to the requested size
-If the array is an even multiple size of the requested size it maps the array multiple times (used to expand across sites)
-If the array is not an even multiple size the function maps the array and throws a warning
-If the array is the same size as the requested size it passes it straight through
-If the array is larger than the instrument sessions it gets shortened and a warning is emitted

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Expand to Requested Array Size.vimd.png "Expand to Requested Array Size.vim")
### **Single SSC DCPower Fill Additional Error info.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Fill Additional Error info.vic.png "Single SSC DCPower Fill Additional Error info.vi")

This VI appends information to the error message from the SSC cluster if an error is on error in, but not initial error.
This makes it easier to debug code since you know what session/site/channel/pin actually threw the error.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Fill Additional Error info.vid.png "Single SSC DCPower Fill Additional Error info.vi")
### **SSC DCPower Get SMU Models.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get SMU Models.vic.png "SSC DCPower Get SMU Models.vi")

This VI gets the 4-digit numerical model number for each DCPower Session.
For exmaple, this will return "4139" for a PXIe-4139 SMU.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Get SMU Models.vid.png "SSC DCPower Get SMU Models.vi")
## **SSC DCPower\Triggers and Events**
### **Single SSC DCPower Export Signal.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Export Signal.vic.png "Single SSC DCPower Export Signal.vi")

Routes signals (triggers and events) to the output terminal you specify for a session.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/Single SSC DCPower Export Signal.vid.png "Single SSC DCPower Export Signal.vi")
### **SSC DCPower Send Software Edge Trigger.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Send Software Edge Trigger.vic.png "SSC DCPower Send Software Edge Trigger.vi")

This VI sends a software edge trigger to every session

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Send Software Edge Trigger.vid.png "SSC DCPower Send Software Edge Trigger.vi")
### **SSC DCPower Wait for Event.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Wait for Event.vic.png "SSC DCPower Wait for Event.vi")

This VI waits until the devices have generated the specified event.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Wait for Event.vid.png "SSC DCPower Wait for Event.vi")
## **SSC DCPower\Waveform Acquisition**
### **SSC DCPower Configure and Start Waveform Acquisition.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure and Start Waveform Acquisition.vic.png "SSC DCPower Configure and Start Waveform Acquisition.vi")

This VI aborts the task, configures the tasks for waveform acquisition, initializes the task and starts the acquisition.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Configure and Start Waveform Acquisition.vid.png "SSC DCPower Configure and Start Waveform Acquisition.vi")
### **SSC DCPower Finish Waveform Acquisition.vi**
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Finish Waveform Acquisition.vic.png "SSC DCPower Finish Waveform Acquisition.vi")

This VI reconfigures the SMU to the previous settings and outputs the samples captured during waveform acquisition.

![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC DCPower Finish Waveform Acquisition.vid.png "SSC DCPower Finish Waveform Acquisition.vi")
