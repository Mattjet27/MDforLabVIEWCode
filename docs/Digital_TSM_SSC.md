## **Digital**
## **Clock Generation**
### **TSM SSC Digital Clock Generator Abort.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Abort.vic.png "TSM SSC Digital Clock Generator Abort.vi")

Stops clock generation on the device(s) connected to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Abort.vid.png "TSM SSC Digital Clock Generator Abort.vi")
### **TSM SSC Digital Clock Generator Generate Clock.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Generate%20Clock.vic.png "TSM SSC Digital Clock Generator Generate Clock.vi")

Configures clock generator frequency and initiates clock generation on the device(s) connected to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Generate%20Clock.vid.png "TSM SSC Digital Clock Generator Generate Clock.vi")
### **TSM SSC Digital Clock Generator Initiate.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Initiate.vic.png "TSM SSC Digital Clock Generator Initiate.vi")

Initiates clock generation on the device(s) connected to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Clock%20Generator%20Initiate.vid.png "TSM SSC Digital Clock Generator Initiate.vi")
## **Configuration**
### **TSM SSC Digital Select Function.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Select%20Function.vic.png "TSM SSC Digital Select Function.vi")

Specifies whether digital pattern instruments connected to the specified pin(s) and pin group(s) are controlled by the PPMU, Digital, disconnected, or off. Changes take effect immediately.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Select%20Function.vid.png "TSM SSC Digital Select Function.vi")
## **Frequency Measurement**
### **TSM SSC Digital Frequency Counter Configure Measurement Time.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Frequency%20Counter%20Configure%20Measurement%20Time.vic.png "TSM SSC Digital Frequency Counter Configure Measurement Time.vi")

Configures the measurement time for the frequency counter on the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Frequency%20Counter%20Configure%20Measurement%20Time.vid.png "TSM SSC Digital Frequency Counter Configure Measurement Time.vi")
### **TSM SSC Digital Frequency Counter Measure Frequency.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Frequency%20Counter%20Measure%20Frequency.vic.png "TSM SSC Digital Frequency Counter Measure Frequency.vi")

Measures the frequency on the specified pin(s) and pin group(s) over the configured measurement time and returns per-site frequency measurements.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Frequency%20Counter%20Measure%20Frequency.vid.png "TSM SSC Digital Frequency Counter Measure Frequency.vi")
## **HRAM**
### **TSM SSC Digital Configure HRAM.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20HRAM.vic.png "TSM SSC Digital Configure HRAM.vi")



![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20HRAM.vid.png "TSM SSC Digital Configure HRAM.vi")
### **TSM SSC Digital Get HRAM Configuration.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20HRAM%20Configuration.vic.png "TSM SSC Digital Get HRAM Configuration.vi")



![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20HRAM%20Configuration.vid.png "TSM SSC Digital Get HRAM Configuration.vi")
### **TSM SSC Digital Log HRAM Results.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Log%20HRAM%20Results.vic.png "TSM SSC Digital Log HRAM Results.vi")

Fetches a defined number of samples for the sites connected to the specified pin(s) and pin group(s). This VI only returns data from sites that are enabled when fetch is called. Returns an array of per-site per-sample data where rows correspond to sites and columns correspond to samples.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Log%20HRAM%20Results.vid.png "TSM SSC Digital Log HRAM Results.vi")
### **TSM SSC Digital Stream HRAM Results.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Stream%20HRAM%20Results.vic.png "TSM SSC Digital Stream HRAM Results.vi")

Fetches a defined number of samples for the sites connected to the specified pin(s) and pin group(s). This VI only returns data from sites that are enabled when fetch is called. Returns an array of per-site per-sample data where rows correspond to sites and columns correspond to samples.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Stream%20HRAM%20Results.vid.png "TSM SSC Digital Stream HRAM Results.vi")
## **Pattern Actions**
### **TSM SSC Digital Abort.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Abort.vic.png "TSM SSC Digital Abort.vi")

Stops bursting the pattern on the specified pin(s) or pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Abort.vid.png "TSM SSC Digital Abort.vi")
### **TSM SSC Digital Burst Pattern [Pass Fail].vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Burst%20Pattern%20[Pass%20Fail].vic.png "TSM SSC Digital Burst Pattern [Pass Fail].vi")

Uses the start label you specify to burst the pattern on the pin(s) and pin group(s) you specify, waits for the burst to complete, and returns per-site pass/fail results.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Burst%20Pattern%20[Pass%20Fail].vid.png "TSM SSC Digital Burst Pattern [Pass Fail].vi")
### **TSM SSC Digital Burst Pattern.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Burst%20Pattern.vic.png "TSM SSC Digital Burst Pattern.vi")

Uses the start label you specify to burst the pattern on the pin(s) and pin group(s) you specify.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Burst%20Pattern.vid.png "TSM SSC Digital Burst Pattern.vi")
### **TSM SSC Digital Get Fail Count.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20Fail%20Count.vic.png "TSM SSC Digital Get Fail Count.vi")

Returns the per-site fail count for the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20Fail%20Count.vid.png "TSM SSC Digital Get Fail Count.vi")
### **TSM SSC Digital Get Site Pass Fail.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20Site%20Pass%20Fail.vic.png "TSM SSC Digital Get Site Pass Fail.vi")

Returns per-site pass/fail results for sites connected to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Get%20Site%20Pass%20Fail.vid.png "TSM SSC Digital Get Site Pass Fail.vi")
### **TSM SSC Digital Wait Until Done.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Wait%20Until%20Done.vic.png "TSM SSC Digital Wait Until Done.vi")

Waits until the pattern burst has completed or the timeout has expired on the specified pin(s) or pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Wait%20Until%20Done.vid.png "TSM SSC Digital Wait Until Done.vi")
## **Pin Levels and Timing**
### **TSM SSC Digital Apply Levels and Timing.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20Levels%20and%20Timing.vic.png "TSM SSC Digital Apply Levels and Timing.vi")

Applies digital levels and timing values defined in previously loaded levels and timing sheets to the device(s) connected to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20Levels%20and%20Timing.vid.png "TSM SSC Digital Apply Levels and Timing.vi")
### **TSM SSC Digital Apply TDR Offsets Per-Site Per-Pin.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20TDR%20Offsets%20Per-Site%20Per-Pin.vic.png "TSM SSC Digital Apply TDR Offsets Per-Site Per-Pin.vi")

Applies the correction for propagation delay offsets to a digital pattern instrument. Use this VI to apply TDR offsets that are stored from a past measurement or are measured by means other than the niDigital TDR VI. Also use this VI to apply correction for offsets if the <B>apply offsets</B> input of the niDigital TDR VI was set to False at the time of measurement.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20TDR%20Offsets%20Per-Site%20Per-Pin.vid.png "TSM SSC Digital Apply TDR Offsets Per-Site Per-Pin.vi")
### **TSM SSC Digital Apply TDR Offsets.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20TDR%20Offsets.vic.png "TSM SSC Digital Apply TDR Offsets.vi")

Applies the correction for propagation delay offsets to digital pattern instrument(s) connected to the specified pin(s) and pin group(s).
Use this VI to apply TDR offsets that are stored from a past measurement or are measured by means other than the niDigital TDR VI. Also use this VI to apply correction for offsets if the apply offsets input of the niDigital TDR VI was set to False at the time of measurement.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Apply%20TDR%20Offsets.vid.png "TSM SSC Digital Apply TDR Offsets.vi")
### **TSM SSC Digital Configure Single Level Per-Site.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Single%20Level%20Per-Site.vic.png "TSM SSC Digital Configure Single Level Per-Site.vi")

Configures and applies the specified per-site levels to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Single%20Level%20Per-Site.vid.png "TSM SSC Digital Configure Single Level Per-Site.vi")
### **TSM SSC Digital Configure Single Level.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Single%20Level.vic.png "TSM SSC Digital Configure Single Level.vi")

Configures and applies the specified single level to the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Single%20Level.vid.png "TSM SSC Digital Configure Single Level.vi")
### **TSM SSC Digital Configure Termination Mode.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Termination%20Mode.vic.png "TSM SSC Digital Configure Termination Mode.vi")

Specifies the behavior of the specified pin(s) and pin group(s) when the pin driver is in a non-drive pin state (L, H, X, V, M, E).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Termination%20Mode.vid.png "TSM SSC Digital Configure Termination Mode.vi")
### **TSM SSC Digital Configure Time Set Compare Edge Per-Site Per-Pin.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge%20Per-Site%20Per-Pin.vic.png "TSM SSC Digital Configure Time Set Compare Edge Per-Site Per-Pin.vi")

Configures the strobe edge time for the specified pins. Use this function to modify time set values after applying a timing sheet with the niDigital Apply Levels and Timing VI, or to create time sets programmatically without the use of timing sheets. This function does not modify the timing sheet file or the timing sheet contents that will be used in future calls to niDigital Apply Levels and Timing; it only affects the values of the current timing context.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge%20Per-Site%20Per-Pin.vid.png "TSM SSC Digital Configure Time Set Compare Edge Per-Site Per-Pin.vi")
### **TSM SSC Digital Configure Time Set Compare Edge Per-Site.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge%20Per-Site.vic.png "TSM SSC Digital Configure Time Set Compare Edge Per-Site.vi")

Configures the strobe edge time for the specified pins. Use this function to modify time set values after applying a timing sheet with the niDigital Apply Levels and Timing VI, or to create time sets programmatically without the use of timing sheets. This function does not modify the timing sheet file or the timing sheet contents that will be used in future calls to niDigital Apply Levels and Timing; it only affects the values of the current timing context.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge%20Per-Site.vid.png "TSM SSC Digital Configure Time Set Compare Edge Per-Site.vi")
### **TSM SSC Digital Configure Time Set Compare Edge.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge.vic.png "TSM SSC Digital Configure Time Set Compare Edge.vi")

Configures the strobe edge time for the specified pins. Use this function to modify time set values after applying a timing sheet with the niDigital Apply Levels and Timing VI, or to create time sets programmatically without the use of timing sheets. This function does not modify the timing sheet file or the timing sheet contents that will be used in future calls to niDigital Apply Levels and Timing; it only affects the values of the current timing context.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Time%20Set%20Compare%20Edge.vid.png "TSM SSC Digital Configure Time Set Compare Edge.vi")
### **TSM SSC Digital Configure Voltage Levels.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Voltage%20Levels.vic.png "TSM SSC Digital Configure Voltage Levels.vi")

Configures voltage levels for the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Configure%20Voltage%20Levels.vid.png "TSM SSC Digital Configure Voltage Levels.vi")
## **PPMU**
### **TSM SSC Digital PPMU Configure Aperture Time.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Aperture%20Time.vic.png "TSM SSC Digital PPMU Configure Aperture Time.vi")

Configures the aperture time for the PPMU measurement on the specified pin(s) and pin group(s).

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Aperture%20Time.vid.png "TSM SSC Digital PPMU Configure Aperture Time.vi")
### **TSM SSC Digital PPMU Configure Current Limit Range.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Current%20Limit%20Range.vic.png "TSM SSC Digital PPMU Configure Current Limit Range.vi")

Specifies the current limit range for the specified pin(s) and pin group(s) when forcing voltage. You must call the PPMU Source VI for changes to the PPMU configuration to take effect, even if the PPMU is already sourcing.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Current%20Limit%20Range.vid.png "TSM SSC Digital PPMU Configure Current Limit Range.vi")
### **TSM SSC Digital PPMU Configure Voltage Limits.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Voltage%20Limits.vic.png "TSM SSC Digital PPMU Configure Voltage Limits.vi")

Specifies the voltage limit high, or high clamp voltage (VCH), and voltage limit low, or low clamp voltage (VCL) for the specified pins and pin group(s) when forcing current. You must call the PPMU Source VI for changes to the PPMU configuration to take effect, even if the PPMU is already sourcing.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Configure%20Voltage%20Limits.vid.png "TSM SSC Digital PPMU Configure Voltage Limits.vi")
### **TSM SSC Digital PPMU Measure Current.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Measure%20Current.vic.png "TSM SSC Digital PPMU Measure Current.vi")

Instructs the PPMU to measure current on the specified pin(s) and pin group(s) and returns per-site per-pin current measurements.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Measure%20Current.vid.png "TSM SSC Digital PPMU Measure Current.vi")
### **TSM SSC Digital PPMU Measure Voltage.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Measure%20Voltage.vic.png "TSM SSC Digital PPMU Measure Voltage.vi")

Instructs the PPMU to measure voltage on the specified pin(s) and pin group(s) and returns per-site per-pin voltage measurements.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Measure%20Voltage.vid.png "TSM SSC Digital PPMU Measure Voltage.vi")
### **TSM SSC Digital PPMU Source Current.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Current.vic.png "TSM SSC Digital PPMU Source Current.vi")

Starts sourcing current from the PPMU on the specified pin(s) and pin group(s). This VI automatically selects the PPMU function. Changes to PPMU source settings do not take effect until you call this VI.


![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Current.vid.png "TSM SSC Digital PPMU Source Current.vi")
### **TSM SSC Digital PPMU Source Voltage Per-Site Per-Pin.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage%20Per-Site%20Per-Pin.vic.png "TSM SSC Digital PPMU Source Voltage Per-Site Per-Pin.vi")

Sources per-site per-pin voltages from the PPMU to the specified pins connected to each site. This  function takes in an array of voltages where rows correspond to sites and columns correspond to pins.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage%20Per-Site%20Per-Pin.vid.png "TSM SSC Digital PPMU Source Voltage Per-Site Per-Pin.vi")
### **TSM SSC Digital PPMU Source Voltage Per-Site.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage%20Per-Site.vic.png "TSM SSC Digital PPMU Source Voltage Per-Site.vi")

Sources per-site voltages from the PPMU on all specified pin(s) and pin group(s) connected to each site. This  function takes in an array of voltages where rows correspond to sites.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage%20Per-Site.vid.png "TSM SSC Digital PPMU Source Voltage Per-Site.vi")
### **TSM SSC Digital PPMU Source Voltage.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage.vic.png "TSM SSC Digital PPMU Source Voltage.vi")

Starts sourcing voltage from the PPMU on the specified pin(s) and pin group(s). This VI automatically selects the PPMU function. Changes to PPMU source settings do not take effect until you call this VI.
a

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source%20Voltage.vid.png "TSM SSC Digital PPMU Source Voltage.vi")
### **TSM SSC Digital PPMU Source.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source.vic.png "TSM SSC Digital PPMU Source.vi")

Starts sourcing voltage or current from the PPMU on the specified pin(s) and pin group(s). This VI automatically selects the PPMU function. Changes to PPMU source settings do not take effect until you call this VI.
s

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20PPMU%20Source.vid.png "TSM SSC Digital PPMU Source.vi")
## **Sequencer Flags and Registers**
### **TSM SSC Digital Read Sequencer Flag.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Sequencer%20Flag.vic.png "TSM SSC Digital Read Sequencer Flag.vi")

Reads the state of a pattern sequencer flag on the device(s) connected to the specified pin(s) and pin group(s). Use pattern sequencer flags to coordinate execution between the pattern sequencer and a runtime test program.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Sequencer%20Flag.vid.png "TSM SSC Digital Read Sequencer Flag.vi")
### **TSM SSC Digital Read Sequencer Register.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Sequencer%20Register.vic.png "TSM SSC Digital Read Sequencer Register.vi")

Reads the value of a pattern sequencer register on the device(s) connected to the specified pin(s) and pin group(s). Use pattern sequencer registers to pass numeric values between the pattern sequencer and a runtime test program.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Sequencer%20Register.vid.png "TSM SSC Digital Read Sequencer Register.vi")
### **TSM SSC Digital Write Sequencer Flag.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Sequencer%20Flag.vic.png "TSM SSC Digital Write Sequencer Flag.vi")

Writes the state of a pattern sequencer flag on the device(s) connected to the specified pin(s) and pin group(s). Use pattern sequencer flags to coordinate execution between the pattern sequencer and a runtime test program.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Sequencer%20Flag.vid.png "TSM SSC Digital Write Sequencer Flag.vi")
### **TSM SSC Digital Write Sequencer Register.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Sequencer%20Register.vic.png "TSM SSC Digital Write Sequencer Register.vi")

Writes a value to a pattern sequencer register on the device(s) connected to the specified pin(s) and pin group(s). Use pattern sequencer registers to pass numeric values between the pattern sequencer and a runtime test program.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Sequencer%20Register.vid.png "TSM SSC Digital Write Sequencer Register.vi")
## **Source and Capture Waveforms**
### **TSM SSC Digital Fetch Capture Waveform.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Fetch%20Capture%20Waveform.vic.png "TSM SSC Digital Fetch Capture Waveform.vi")

Fetches a defined number of samples for the sites connected to the specified pin(s) and pin group(s). This VI only returns data from sites that are enabled when fetch is called. Returns an array of per-site per-sample data where rows correspond to sites and columns correspond to samples.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Fetch%20Capture%20Waveform.vid.png "TSM SSC Digital Fetch Capture Waveform.vi")
### **TSM SSC Digital Write Source Waveform [Broadcast].vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Source%20Waveform%20[Broadcast].vic.png "TSM SSC Digital Write Source Waveform [Broadcast].vi")

Writes the same waveform data to all sites connected to the specified pin(s) and pin group(s). Use this instance of the niDigital Write Source Waveform VI if you set the data mapping parameter of your source waveform to Broadcast.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Source%20Waveform%20[Broadcast].vid.png "TSM SSC Digital Write Source Waveform [Broadcast].vi")
### **TSM SSC Digital Write Source Waveform [Site Unique].vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Source%20Waveform%20[Site%20Unique].vic.png "TSM SSC Digital Write Source Waveform [Site Unique].vi")

Writes one waveform per site after a waveform is created. Use this VI if you set the data mapping parameter of your source waveform to Site Unique. This VI accepts an array of per-site waveforms, where rows correspond to sites and columns correspond to samples.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Source%20Waveform%20[Site%20Unique].vid.png "TSM SSC Digital Write Source Waveform [Site Unique].vi")
## **Static**
### **TSM SSC Digital Read Static.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Static.vic.png "TSM SSC Digital Read Static.vi")

Reads the current state of comparators for the specified pin(s) and pin group(s). If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins. Returns an array of per-site per-pin static states.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Read%20Static.vid.png "TSM SSC Digital Read Static.vi")
### **TSM SSC Digital Write Static Per-Site Per-Pin.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static%20Per-Site%20Per-Pin.vic.png "TSM SSC Digital Write Static Per-Site Per-Pin.vi")

Writes per-site per-pin static states to the specified pin(s) and pin group(s). The selected pins remain in the specified state until the next pattern burst or call to this VI. If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins.
This VI does not change the selected pin function. If you write a static state to a pin that does not have the Digital function selected, the new static state is stored by the digital pattern instrument, and affects the state of the pin the next time you change the selected function to Digital.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static%20Per-Site%20Per-Pin.vid.png "TSM SSC Digital Write Static Per-Site Per-Pin.vi")
### **TSM SSC Digital Write Static Per-Site.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static%20Per-Site.vic.png "TSM SSC Digital Write Static Per-Site.vi")

Writes per-site static states to the specified pin(s) and pin group(s). The selected pins remain in the specified state until the next pattern burst or call to this VI. If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins.
This VI does not change the selected pin function. If you write a static state to a pin that does not have the Digital function selected, the new static state is stored by the digital pattern instrument, and affects the state of the pin the next time you change the selected function to Digital.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static%20Per-Site.vid.png "TSM SSC Digital Write Static Per-Site.vi")
### **TSM SSC Digital Write Static.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static.vic.png "TSM SSC Digital Write Static.vi")

Writes a static state to all specified pin(s) and pin group(s). The selected pins remain in the specified state until the next pattern burst or call to this VI. If there are uncommitted changes to levels or the termination mode, this VI commits the changes to the pins.
This VI does not change the selected pin function. If you write a static state to a pin that does not have the Digital function selected, the new static state is stored by the digital pattern instrument, and affects the state of the pin the next time you change the selected function to Digital.


![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Write%20Static.vid.png "TSM SSC Digital Write Static.vi")
## **SubVIs**
### **Digital Apply LUT.vim**
![alt text](/docs/images/Digital/Digital%20Apply%20LUT.vimc.png "Digital Apply LUT.vim")



![alt text](/docs/images/Digital/Digital%20Apply%20LUT.vimd.png "Digital Apply LUT.vim")
### **Digital Arrange Channels Per-Site.vi**
![alt text](/docs/images/Digital/Digital%20Arrange%20Channels%20Per-Site.vic.png "Digital Arrange Channels Per-Site.vi")



![alt text](/docs/images/Digital/Digital%20Arrange%20Channels%20Per-Site.vid.png "Digital Arrange Channels Per-Site.vi")
### **Digital Channel List to Pins.vi**
![alt text](/docs/images/Digital/Digital%20Channel%20List%20to%20Pins.vic.png "Digital Channel List to Pins.vi")



![alt text](/docs/images/Digital/Digital%20Channel%20List%20to%20Pins.vid.png "Digital Channel List to Pins.vi")
### **Digital Site List to Site Numbers.vi**
![alt text](/docs/images/Digital/Digital%20Site%20List%20to%20Site%20Numbers.vic.png "Digital Site List to Site Numbers.vi")



![alt text](/docs/images/Digital/Digital%20Site%20List%20to%20Site%20Numbers.vid.png "Digital Site List to Site Numbers.vi")
### **Pass-Fail Boolean to Pass-Fail String.vi**
![alt text](/docs/images/Digital/Pass-Fail%20Boolean%20to%20Pass-Fail%20String.vic.png "Pass-Fail Boolean to Pass-Fail String.vi")



![alt text](/docs/images/Digital/Pass-Fail%20Boolean%20to%20Pass-Fail%20String.vid.png "Pass-Fail Boolean to Pass-Fail String.vi")
### **Pin State to String.vi**
![alt text](/docs/images/Digital/Pin%20State%20to%20String.vic.png "Pin State to String.vi")



![alt text](/docs/images/Digital/Pin%20State%20to%20String.vid.png "Pin State to String.vi")
### **SSC Digital Calculate Per-Instrument Per-Site to Per-Site LUT.vi**
![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20Per-Site%20to%20Per-Site%20LUT.vic.png "SSC Digital Calculate Per-Instrument Per-Site to Per-Site LUT.vi")



![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20Per-Site%20to%20Per-Site%20LUT.vid.png "SSC Digital Calculate Per-Instrument Per-Site to Per-Site LUT.vi")
### **SSC Digital Calculate Per-Instrument to Per-Site LUT.vi**
![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20to%20Per-Site%20LUT.vic.png "SSC Digital Calculate Per-Instrument to Per-Site LUT.vi")



![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20to%20Per-Site%20LUT.vid.png "SSC Digital Calculate Per-Instrument to Per-Site LUT.vi")
### **SSC Digital Calculate Per-Instrument to Per-Site Per-Pin LUT.vi**
![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20to%20Per-Site%20Per-Pin%20LUT.vic.png "SSC Digital Calculate Per-Instrument to Per-Site Per-Pin LUT.vi")



![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Instrument%20to%20Per-Site%20Per-Pin%20LUT.vid.png "SSC Digital Calculate Per-Instrument to Per-Site Per-Pin LUT.vi")
### **SSC Digital Calculate Per-Site Per-Pin to Per-Instrument LUT.vi**
![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Site%20Per-Pin%20to%20Per-Instrument%20LUT.vic.png "SSC Digital Calculate Per-Site Per-Pin to Per-Instrument LUT.vi")



![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Site%20Per-Pin%20to%20Per-Instrument%20LUT.vid.png "SSC Digital Calculate Per-Site Per-Pin to Per-Instrument LUT.vi")
### **SSC Digital Calculate Per-Site to Per-Instrument LUT.vi**
![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Site%20to%20Per-Instrument%20LUT.vic.png "SSC Digital Calculate Per-Site to Per-Instrument LUT.vi")



![alt text](/docs/images/Digital/SSC%20Digital%20Calculate%20Per-Site%20to%20Per-Instrument%20LUT.vid.png "SSC Digital Calculate Per-Site to Per-Instrument LUT.vi")
### **Trim Whitespace [Inlined].vi**
![alt text](/docs/images/Digital/Trim%20Whitespace%20[Inlined].vic.png "Trim Whitespace [Inlined].vi")

Removes all ASCII white space (spaces, tabs, carriage returns, and linefeeds) from the beginning, end, or both ends of <B>string</B>. The Trim Whitespace VI does not remove double byte characters.

![alt text](/docs/images/Digital/Trim%20Whitespace%20[Inlined].vid.png "Trim Whitespace [Inlined].vi")
## **TSM**
### **TSM Digital Close Sessions.vi**
![alt text](/docs/images/Digital/TSM%20Digital%20Close%20Sessions.vic.png "TSM Digital Close Sessions.vi")

Use this VI to reset and close all sessions for all NI-Digital Pattern instruments in the Semiconductor Module Context.

![alt text](/docs/images/Digital/TSM%20Digital%20Close%20Sessions.vid.png "TSM Digital Close Sessions.vi")
### **TSM Digital Initialize Sessions.vi**
![alt text](/docs/images/Digital/TSM%20Digital%20Initialize%20Sessions.vic.png "TSM Digital Initialize Sessions.vi")

Use this VI to initialize sessions for all NI-Digital Pattern instruments in the pin map associated with the test program and apply an initial level and timing sheet to these instruments. 

![alt text](/docs/images/Digital/TSM%20Digital%20Initialize%20Sessions.vid.png "TSM Digital Initialize Sessions.vi")
### **TSM SSC Digital 1 Pin To N Sessions.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%201%20Pin%20To%20N%20Sessions.vic.png "TSM SSC Digital 1 Pin To N Sessions.vi")

Populates the TSM SSC Digital cluster for the specified pin.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%201%20Pin%20To%20N%20Sessions.vid.png "TSM SSC Digital 1 Pin To N Sessions.vi")
### **TSM SSC Digital Filter Sites.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Filter%20Sites.vic.png "TSM SSC Digital Filter Sites.vi")

Use this VI to filter the Digital Cluster to contain only sessions and information pertaining to the desired sites. Note that the cluster information output by this function may be used for instrument control but should NOT be used to publish data to TSM.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Filter%20Sites.vid.png "TSM SSC Digital Filter Sites.vi")
### **TSM SSC Digital N Pins To M Sessions.vi**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20N%20Pins%20To%20M%20Sessions.vic.png "TSM SSC Digital N Pins To M Sessions.vi")

Populates the TSM SSC Digital cluster for the specified pin(s) and pin group(s). 
The "Turn Pin Groups to Pins?" should be set to TRUE when using pin groups, since it's important for the TSM SSC functions to have a full list of DUT pins when mapping instrument indexed results into per-site per-pin results.
The "Turn Pin Groups to Pins?" input can be set to FALSE <b>if the Pins input doesn't contain any pin groups</b>. This setting is preferred when optimizing test time.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20N%20Pins%20To%20M%20Sessions.vid.png "TSM SSC Digital N Pins To M Sessions.vi")
### **TSM SSC Digital Publish.vim**
![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Publish.vimc.png "TSM SSC Digital Publish.vim")

Publishes measurement data for one or more pins to the Semiconductor Multi Test step type instances for all sites in the Semiconductor Module context. Use this VI to publish per-site data with a pin query context.

![alt text](/docs/images/Digital/TSM%20SSC%20Digital%20Publish.vimd.png "TSM SSC Digital Publish.vim")
