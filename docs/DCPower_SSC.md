## **SSC DCPower**
### **SSC DCPower Configure Measurements.vi**
<<<<<<< HEAD
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Measurements.vic.png "SSC DCPower Configure Measurements.vi")
=======
<<<<<<< HEAD
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/docs/images/DCPower/SSC DCPower Configure Measurements.vic.png "SSC DCPower Configure Measurements.vi")
=======
![alt text](https://github.com/Mattjet27/MDforLabVIEWCode/images/DCPower/SSC%20DCPower%20Configure%20Measurements.vic.png "SSC DCPower Configure Measurements.vi")
>>>>>>> refs/remotes/origin/master
>>>>>>> refs/remotes/origin/master

This VI configures the measurement mode for the sessions.
The (Auto) setting automatically chooses the optimal measurement mode individually for the instrument model in each session.
From a test time perspective Software Triggered measurements are better than using Measure Multiple, but Software Triggering isn't supported by all devices, and enabling them can make debugging in the Digital Pattern Editor more difficult.
Measure Multiple works for all devices and allows for easier debugging, but it takes longer to fetch measurements than the Software Triggered method.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Measurements.vid.png "SSC DCPower Configure Measurements.vi")
### **SSC DCPower Configure Settings.vim**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Settings.vimc.png "SSC DCPower Configure Settings.vim")

This VI configures important DCPower channel settings for the sessions.
Settings are ignored if they aren't supported by the devices being used.
Note inputs are recommended, and each can be single elements or arrays.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Settings.vimd.png "SSC DCPower Configure Settings.vim")
### **SSC DCPower Force Current Asymmetric Limits.vim**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Asymmetric%20Limits.vimc.png "SSC DCPower Force Current Asymmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Asymmetric%20Limits.vimd.png "SSC DCPower Force Current Asymmetric Limits.vim")
### **SSC DCPower Force Current Symmetric Limits.vim**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Symmetric%20Limits.vimc.png "SSC DCPower Force Current Symmetric Limits.vim")

This VI forces current on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Symmetric%20Limits.vimd.png "SSC DCPower Force Current Symmetric Limits.vim")
### **SSC DCPower Force Voltage Asymmetric Limits.vim**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Asymmetric%20Limits.vimc.png "SSC DCPower Force Voltage Asymmetric Limits.vim")

This VI forces voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Asymmetric%20Limits.vimd.png "SSC DCPower Force Voltage Asymmetric Limits.vim")
### **SSC DCPower Force Voltage Symmetric Limits.vim**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Symmetric%20Limits.vimc.png "SSC DCPower Force Voltage Symmetric Limits.vim")

This VI forces voltage on the sessions.
Note all level and limit inputs can be single elements or arrays, as needed by the test.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Symmetric%20Limits.vimd.png "SSC DCPower Force Voltage Symmetric Limits.vim")
### **SSC DCPower Measure.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Measure.vic.png "SSC DCPower Measure.vi")

This VI takes a Voltage and Current measurement for each session.
Measurement Mode is a recommended input. The Auto setting will check the measurement mode for each session and use the appropriate measurement method per session.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Measure.vid.png "SSC DCPower Measure.vi")
## **SSC DCPower\Control**
### **SSC DCPower Abort.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Abort.vic.png "SSC DCPower Abort.vi")

Transitions the NI-DCPower sessions from the Running state to the Committed state. If a sequence is running, it is stopped.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Abort.vid.png "SSC DCPower Abort.vi")
### **SSC DCPower Commit.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Commit.vic.png "SSC DCPower Commit.vi")

Applies previously configured settings to the device. Calling this VI moves the NI-DCPower sessions from the Uncommitted state into the Committed state.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Commit.vid.png "SSC DCPower Commit.vi")
### **SSC DCPower Initiate.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Initiate.vic.png "SSC DCPower Initiate.vi")

Starts generation or acquisition, causing the NI-DCPower sessions to leave the Uncommitted state or Committed state and enter the Running state.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Initiate.vid.png "SSC DCPower Initiate.vi")
### **SSC DCPower Reset Channels.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Reset%20Channels.vic.png "SSC DCPower Reset Channels.vi")

Resets the device to a known state. This VI disables power generation, resets session properties to their default values, commits the session properties, and leaves the sessions in the Uncommitted state. You can use this VI to clear certain errors in less time than using niDCPower Reset Device VI. Refer to the Programming States topic in the NI DC Power Supplies and SMUs Help for more information about NI-DCPower software states.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Reset%20Channels.vid.png "SSC DCPower Reset Channels.vi")
## **SSC DCPower\Measure**
### **Single SSC DCPower Configure Settings.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Settings.vic.png "Single SSC DCPower Configure Settings.vi")

This VI configures important DCPower channel settings for a session.
Settings are ignored if they aren't supported by the device being used.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Settings.vid.png "Single SSC DCPower Configure Settings.vi")
### **Single SSC DCPower Get Aperture Times in Seconds.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Get%20Aperture%20Times%20in%20Seconds.vic.png "Single SSC DCPower Get Aperture Times in Seconds.vi")

This VI gets the measurement aperture time of the session in seconds (if it was set in units of PLCs, it converts it to seconds).

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Get%20Aperture%20Times%20in%20Seconds.vid.png "Single SSC DCPower Get Aperture Times in Seconds.vi")
### **SSC DCPower Configure Aperture Time with Abort and Initiate.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Aperture%20Time%20with%20Abort%20and%20Initiate.vic.png "SSC DCPower Configure Aperture Time with Abort and Initiate.vi")

This VI aborts, configures measurement aperture time, and initializes the sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Aperture%20Time%20with%20Abort%20and%20Initiate.vid.png "SSC DCPower Configure Aperture Time with Abort and Initiate.vi")
### **SSC DCPower Configure Aperture Time.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Aperture%20Time.vic.png "SSC DCPower Configure Aperture Time.vi")

This VI configures measurement aperture time of the sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Aperture%20Time.vid.png "SSC DCPower Configure Aperture Time.vi")
### **SSC DCPower Configure Power Line Frequency.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Power%20Line%20Frequency.vic.png "SSC DCPower Configure Power Line Frequency.vi")

This VI configures the power line frequency of the sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Power%20Line%20Frequency.vid.png "SSC DCPower Configure Power Line Frequency.vi")
### **SSC DCPower Configure Sense.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Sense.vic.png "SSC DCPower Configure Sense.vi")

This VI configures local or remote sense for the sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Sense.vid.png "SSC DCPower Configure Sense.vi")
### **SSC DCPower Configure Settings Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Settings%20Array.vic.png "SSC DCPower Configure Settings Array.vi")

This VI configures important DCPower channel settings for the sessions.
Settings are ignored if they aren't supported by the device being used.
Note all inputs are required, and all need to be populated with values for every session.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Settings%20Array.vid.png "SSC DCPower Configure Settings Array.vi")
### **SSC DCPower Debug Global.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Debug%20Global.vic.png "SSC DCPower Debug Global.vi")



![alt text](/docs/images/DCPower/SSC%20DCPower%20Debug%20Global.vid.png "SSC DCPower Debug Global.vi")
### **SSC DCPower Get Aperture Times in Seconds.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Aperture%20Times%20in%20Seconds.vic.png "SSC DCPower Get Aperture Times in Seconds.vi")

This VI gets the measurement aperture time of the sessions in seconds (if it was set in units of PLCs, it converts it to seconds).

![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Aperture%20Times%20in%20Seconds.vid.png "SSC DCPower Get Aperture Times in Seconds.vi")
### **SSC DCPower Get Power Line Frequencies.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Power%20Line%20Frequencies.vic.png "SSC DCPower Get Power Line Frequencies.vi")

This VI gets the configured power line frequency for the sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Power%20Line%20Frequencies.vid.png "SSC DCPower Get Power Line Frequencies.vi")
## **SSC DCPower\Query**
### **SSC DCPower Query In Compliance.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Query%20In%20Compliance.vic.png "SSC DCPower Query In Compliance.vi")

Queries the specified output channels to determine if they is operating at the compliance limits.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Query%20In%20Compliance.vid.png "SSC DCPower Query In Compliance.vi")
### **SSC DCPower Query Output State.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Query%20Output%20State.vic.png "SSC DCPower Query Output State.vi")

Queries the specified output channel to determine if the output channels are currently in the state specified by <B>output state</B>.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Query%20Output%20State.vid.png "SSC DCPower Query Output State.vi")
## **SSC DCPower\Source**
### **SSC DCPower Configure Output Connected.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Connected.vic.png "SSC DCPower Configure Output Connected.vi")

This VI configures output enabled on the channels.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Connected.vid.png "SSC DCPower Configure Output Connected.vi")
### **SSC DCPower Configure Output Enabled And Connected.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Enabled%20And%20Connected.vic.png "SSC DCPower Configure Output Enabled And Connected.vi")

This VI configures output enabled and connected on the channels.
T - Enable and then connect
F - Disconnect and then disable

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Enabled%20And%20Connected.vid.png "SSC DCPower Configure Output Enabled And Connected.vi")
### **SSC DCPower Configure Output Enabled.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Enabled.vic.png "SSC DCPower Configure Output Enabled.vi")

This VI configures output enabled on the channels.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Enabled.vid.png "SSC DCPower Configure Output Enabled.vi")
### **SSC DCPower Configure Output Function.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Function.vic.png "SSC DCPower Configure Output Function.vi")

This VI configures the output function of the instrument sessions. The tasks must be aborted when calling this method.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Function.vid.png "SSC DCPower Configure Output Function.vi")
### **SSC DCPower Configure Output Resistance Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Resistance%20Array.vic.png "SSC DCPower Configure Output Resistance Array.vi")

This VI configures output resistance on the channels.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Resistance%20Array.vid.png "SSC DCPower Configure Output Resistance Array.vi")
### **SSC DCPower Configure Output Resistance.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Resistance.vic.png "SSC DCPower Configure Output Resistance.vi")

This VI configures output resistance on the channels.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Output%20Resistance.vid.png "SSC DCPower Configure Output Resistance.vi")
### **SSC DCPower Configure Source Delay.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Delay.vic.png "SSC DCPower Configure Source Delay.vi")

This VI configures the Source Delay.
This can be used when in the single point mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Delay.vid.png "SSC DCPower Configure Source Delay.vi")
### **SSC DCPower Configure Source Mode.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Mode.vic.png "SSC DCPower Configure Source Mode.vi")

This VI configures the sourcing mode of the instrument sessions. The tasks must be aborted when calling this method.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Mode.vid.png "SSC DCPower Configure Source Mode.vi")
### **SSC DCPower Get Max Current.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Max%20Current.vic.png "SSC DCPower Get Max Current.vi")

This VI returns the max Current (A) Range for each DCPower Session.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Max%20Current.vid.png "SSC DCPower Get Max Current.vi")
## **SSC DCPower\Source\Constant Current**
### **Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Current%20Asymmetric%20Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi")

This VI configures the sessions to force a single point DC current level with asymmetic voltage limits.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Current%20Asymmetric%20Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Current Asymmetric Limits.vi")
### **Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Current%20Symmetric%20Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi")

This VI configures the sessions to force a single point DC current level with a voltage limit.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Current%20Symmetric%20Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Current Symmetric Limits.vi")
### **SSC DCPower Configure Current Level Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level%20Array.vic.png "SSC DCPower Configure Current Level Array.vi")

This VI configures the Current Level with an array input. This properly expands the array as needed to apply to all sessions.
This can be used when in the single point current mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level%20Array.vid.png "SSC DCPower Configure Current Level Array.vi")
### **SSC DCPower Configure Current Level Range.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level%20Range.vic.png "SSC DCPower Configure Current Level Range.vi")

This VI configures the current level range. 
The range can be set when the device is in single point current mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level%20Range.vid.png "SSC DCPower Configure Current Level Range.vi")
### **SSC DCPower Configure Current Level.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level.vic.png "SSC DCPower Configure Current Level.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Level.vid.png "SSC DCPower Configure Current Level.vi")
### **SSC DCPower Configure Voltage Limit Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit%20Array.vic.png "SSC DCPower Configure Voltage Limit Array.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit%20Array.vid.png "SSC DCPower Configure Voltage Limit Array.vi")
### **SSC DCPower Configure Voltage Limit Range.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit%20Range.vic.png "SSC DCPower Configure Voltage Limit Range.vi")

This VI configures the voltage limit range. 
The range can be set when the device is in single point current mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit%20Range.vid.png "SSC DCPower Configure Voltage Limit Range.vi")
### **SSC DCPower Configure Voltage Limit.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit.vic.png "SSC DCPower Configure Voltage Limit.vi")

This VI configures the Current Level.
This can be used when in the single point current mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Limit.vid.png "SSC DCPower Configure Voltage Limit.vi")
### **SSC DCPower Force Current Array Asymmetric Limits.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Array%20Asymmetric%20Limits.vic.png "SSC DCPower Force Current Array Asymmetric Limits.vi")

This VI sources current on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Array%20Asymmetric%20Limits.vid.png "SSC DCPower Force Current Array Asymmetric Limits.vi")
### **SSC DCPower Force Current Array Symmetric Limits.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Array%20Symmetric%20Limits.vic.png "SSC DCPower Force Current Array Symmetric Limits.vi")

This VI forces current on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Current%20Array%20Symmetric%20Limits.vid.png "SSC DCPower Force Current Array Symmetric Limits.vi")
## **SSC DCPower\Source\Constant Voltage**
### **Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Voltage%20Asymmetric%20Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi")

This VI configures the instrument sessions to force a single voltage with asymmetric current limits.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Voltage%20Asymmetric%20Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Voltage Asymmetric Limits.vi")
### **Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Voltage%20Symmetric%20Limits.vic.png "Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi")

This VI configures the instrument sessions to force a single voltage.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Configure%20Single%20Point%20Force%20DC%20Voltage%20Symmetric%20Limits.vid.png "Single SSC DCPower Configure Single Point Force DC Voltage Symmetric Limits.vi")
### **SSC DCPower Configure Current Limit Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit%20Array.vic.png "SSC DCPower Configure Current Limit Array.vi")

This VI configures the Current Limit.
This can be used when in the single point voltage mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit%20Array.vid.png "SSC DCPower Configure Current Limit Array.vi")
### **SSC DCPower Configure Current Limit Range.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit%20Range.vic.png "SSC DCPower Configure Current Limit Range.vi")

This VI configures the current limit range. 
The range can be set when the device is in single point voltage mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit%20Range.vid.png "SSC DCPower Configure Current Limit Range.vi")
### **SSC DCPower Configure Current Limit.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit.vic.png "SSC DCPower Configure Current Limit.vi")

This VI configures the Current Limit.
This can be used when in the single point voltage mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Current%20Limit.vid.png "SSC DCPower Configure Current Limit.vi")
### **SSC DCPower Configure Voltage Level Array.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level%20Array.vic.png "SSC DCPower Configure Voltage Level Array.vi")

This VI configures the Voltage Level with an array input. This properly expands the array as needed to apply to all sessions.
This can be used when in the single point voltage mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level%20Array.vid.png "SSC DCPower Configure Voltage Level Array.vi")
### **SSC DCPower Configure Voltage Level Range.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level%20Range.vic.png "SSC DCPower Configure Voltage Level Range.vi")

This VI configures the voltage level range. 
The range can be set when the device is in single point voltage mode. When changing ranges in the Running state, be aware of the order of the output range and output value changes because the configuration change takes effect immediately in this state. If a range is selected that does not match the valid ranges for a device, the range is coerced to the next-highest range.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level%20Range.vid.png "SSC DCPower Configure Voltage Level Range.vi")
### **SSC DCPower Configure Voltage Level.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level.vic.png "SSC DCPower Configure Voltage Level.vi")

This VI configures the Voltage Level.
This can be used when in the single point voltage mode.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Voltage%20Level.vid.png "SSC DCPower Configure Voltage Level.vi")
### **SSC DCPower Force Voltage Array Asymmetric Limits.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Array%20Asymmetric%20Limits.vic.png "SSC DCPower Force Voltage Array Asymmetric Limits.vi")

This VI forces voltage on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Array%20Asymmetric%20Limits.vid.png "SSC DCPower Force Voltage Array Asymmetric Limits.vi")
### **SSC DCPower Force Voltage Array Symmetric Limits.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Array%20Symmetric%20Limits.vic.png "SSC DCPower Force Voltage Array Symmetric Limits.vi")

This VI forces voltage on the provided sessions.
All input arrays need to be populated with a value for each session, or else the for loop won't iterate for all sessions.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Force%20Voltage%20Array%20Symmetric%20Limits.vid.png "SSC DCPower Force Voltage Array Symmetric Limits.vi")
## **SSC DCPower\Source\Source Adapt**
### **SSC DCPower Configure Source Adapt.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Adapt.vic.png "SSC DCPower Configure Source Adapt.vi")

This VI configures Source Adapt parameters for the channels and sets them to the Custom transient response setting.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Source%20Adapt.vid.png "SSC DCPower Configure Source Adapt.vi")
### **SSC DCPower Configure Transient Response.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Transient%20Response.vic.png "SSC DCPower Configure Transient Response.vi")

This VI configures the transient response setting for the channel.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20Transient%20Response.vid.png "SSC DCPower Configure Transient Response.vi")
### **SSC DCPower Get Source Adapt Settings.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Source%20Adapt%20Settings.vic.png "SSC DCPower Get Source Adapt Settings.vi")

This VI gets the transient response settings (e.g. Source Adapt parameters) for the channels.
This can be used to get the source adapt parameters for the default transient response settings (Slow, Normal, Fast) if the channels are in those modes.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20Source%20Adapt%20Settings.vid.png "SSC DCPower Get Source Adapt Settings.vi")
## **SSC DCPower\SubVIs**
### **DCPower Model to Ranges.vi**
![alt text](/docs/images/DCPower/DCPower%20Model%20to%20Ranges.vic.png "DCPower Model to Ranges.vi")

This VI takes a DCPower Model Number (such as "4139") and outupts it's Voltage, Current, and Output Resistance (if supported) ranges.
For devices that don't support Output Resistance, the array returned will be empty for the ranges.

![alt text](/docs/images/DCPower/DCPower%20Model%20to%20Ranges.vid.png "DCPower Model to Ranges.vi")
### **Expand to Requested Array Size.vim**
![alt text](/docs/images/DCPower/Expand%20to%20Requested%20Array%20Size.vimc.png "Expand to Requested Array Size.vim")

This VI expands the array in to the requested size.
Cases:
-If both sizes are zero, this function does nothing (no error)
-If the array is empty this function generates an array of default type and throws an error
-If the array has one element the function maps it to the requested size
-If the array is an even multiple size of the requested size it maps the array multiple times (used to expand across sites)
-If the array is not an even multiple size the function maps the array and throws a warning
-If the array is the same size as the requested size it passes it straight through
-If the array is larger than the instrument sessions it gets shortened and a warning is emitted

![alt text](/docs/images/DCPower/Expand%20to%20Requested%20Array%20Size.vimd.png "Expand to Requested Array Size.vim")
### **Single SSC DCPower Fill Additional Error info.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Fill%20Additional%20Error%20info.vic.png "Single SSC DCPower Fill Additional Error info.vi")

This VI appends information to the error message from the SSC cluster if an error is on error in, but not initial error.
This makes it easier to debug code since you know what session/site/channel/pin actually threw the error.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Fill%20Additional%20Error%20info.vid.png "Single SSC DCPower Fill Additional Error info.vi")
### **SSC DCPower Get SMU Models.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20SMU%20Models.vic.png "SSC DCPower Get SMU Models.vi")

This VI gets the 4-digit numerical model number for each DCPower Session.
For exmaple, this will return "4139" for a PXIe-4139 SMU.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Get%20SMU%20Models.vid.png "SSC DCPower Get SMU Models.vi")
## **SSC DCPower\Triggers and Events**
### **Single SSC DCPower Export Signal.vi**
![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Export%20Signal.vic.png "Single SSC DCPower Export Signal.vi")

Routes signals (triggers and events) to the output terminal you specify for a session.

![alt text](/docs/images/DCPower/Single%20SSC%20DCPower%20Export%20Signal.vid.png "Single SSC DCPower Export Signal.vi")
### **SSC DCPower Send Software Edge Trigger.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Send%20Software%20Edge%20Trigger.vic.png "SSC DCPower Send Software Edge Trigger.vi")

This VI sends a software edge trigger to every session

![alt text](/docs/images/DCPower/SSC%20DCPower%20Send%20Software%20Edge%20Trigger.vid.png "SSC DCPower Send Software Edge Trigger.vi")
### **SSC DCPower Wait for Event.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Wait%20for%20Event.vic.png "SSC DCPower Wait for Event.vi")

This VI waits until the devices have generated the specified event.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Wait%20for%20Event.vid.png "SSC DCPower Wait for Event.vi")
## **SSC DCPower\Waveform Acquisition**
### **SSC DCPower Configure and Start Waveform Acquisition.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20and%20Start%20Waveform%20Acquisition.vic.png "SSC DCPower Configure and Start Waveform Acquisition.vi")

This VI aborts the task, configures the tasks for waveform acquisition, initializes the task and starts the acquisition.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Configure%20and%20Start%20Waveform%20Acquisition.vid.png "SSC DCPower Configure and Start Waveform Acquisition.vi")
### **SSC DCPower Finish Waveform Acquisition.vi**
![alt text](/docs/images/DCPower/SSC%20DCPower%20Finish%20Waveform%20Acquisition.vic.png "SSC DCPower Finish Waveform Acquisition.vi")

This VI reconfigures the SMU to the previous settings and outputs the samples captured during waveform acquisition.

![alt text](/docs/images/DCPower/SSC%20DCPower%20Finish%20Waveform%20Acquisition.vid.png "SSC DCPower Finish Waveform Acquisition.vi")
