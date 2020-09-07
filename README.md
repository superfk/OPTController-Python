# OPTController-Python
> OPTController with Python version

## Code Examples
Read Intensity:<br />
`opt = OPTController()`<br />
`opt.open('192.168.1.16')`<br />
`intensity = opt.readIntensity(channelIndex=1)`<br />
`opt.close()`<br />

Set Intensity:<br />
`opt = OPTController()`<br />
`opt.open('192.168.1.16')`<br />
`opt.setIntensity(channelIndex=1, intensity=100)`<br />
`opt.close()`<br />
