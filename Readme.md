#flightPanel-speed

Re-usable Speed indicator Web Component refactored from flightSimPanels as 
Custom Element in Polymer.

`<flightPanel-speed width=200 height=200 speed=25></flightPanel-speed>`

<p align="center">
  <img src="speedIndicator.png?raw=true" alt="Speed Indicator 200 x 200 px"/>
</p>

This Custom Element is derived from Polymer's 
[seed-element](https://github.com/PolymerLabs/seed-element)
according to the 
[guide lines "Creating reusable elements:
 How to publish and deploy reusable Polymer elements on GitHub"]
(http://www.polymer-project.org/docs/start/reusableelements.html) .

The Speed indicator is scaled to the top speed 49 kts of SolarImpulse2.
Its native resolution and default width & height are 300 px.

The Custom Element accepts attributes width, height, and speed.
See demo.html for example.
