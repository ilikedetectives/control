# Control
Photomode Range Unlocker for Control by Remedy Entertainment

## Getting Started
### Prerequisites
[Loose File Loader](https://www.nexusmods.com/control/mods/11) by reg2k

### Installation
#### Scenario #1: If you don't have any Tweakables installed yet
1. Simply extract the zip file and paste the tweakables.xml file like this path indicated 
```
Control\data\globaldb\tweakables.xml
```
2. Done

#### Scenario #2: You already have Tweakables already installed
1. Go to where you have your current tweakables.xml file is installed Control\data\globaldb\tweakables.xml and paste the following: 
```
<tweakable type="float1" name="Photo Mode Camera:Max Range(m)" value="300.000000"/>.
```
2. Save and Close your tweakables.xml
3. Done

### Notes
- Works for both DX11 and DX12 version as of 1.09 update
- This is NOT a freecam, which means you cannot move the camera through objects (like going through walls)
- I also included the following 5 parameters for photomode with their default values in case you need to adjust them to your liking in the tweakables.xml file. If you like the defaul values, then you don't have to do anything else.
- Making the camera goes too fast will make it harder to take portrait photos if that's what you're interested in.
```
<tweakable type="float1" name="Photo Mode Camera:Camera Mouse Rotation Speed (deg/s)" value="10.000000"/>
<tweakable type="float1" name="Photo Mode Camera:Camera Movement Speed (m/s)" value="3.000000"/>
<tweakable type="float1" name="Photo Mode Camera:Camera Stick Rotation Speed (deg/s)" value="280.000000"/>
<tweakable type="float1" name="Photo Mode Camera:Camera Vertical Movement Speed (m/s)" value="2.000000"/>
<tweakable type="float1" name="Camera:Photo Mode Near Plane" value="0.100000"/>
```

## Acknowledgement
* Special thanks to reg2k for making the [Loose File Loader](https://www.nexusmods.com/control/mods/11) and sharing all these [tweakables](https://www.nexusmods.com/control/mods/14) provided by Remedy with the modding community.

## Donation
If you like my work, you can support me via [Ko-fi](https://ko-fi.com/ilikedetectives) or [Paypal](https://www.paypal.com/paypalme2/colin9999). Thank you so much!

