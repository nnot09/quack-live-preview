### QUACKQUACK LIVE ###
external gaming chair for Quake Live (version 1096 win-x86)

features
* configurable aimbot
  - key/auto shoot (tbd)
  - smoothing (off, linear, snap, lock, dynamic)
  - fov
  - prediction (basic but includes velocity + tth)
  - vis check (tbd, probably map-parsing)
  - target lock (or target auto switch if turned off, disabled when auto shoot)
  - target selection mode (closest to crosshair, closest to player (tbd))

* railgun/shotgun triggerbot
  - ray tracing based triggerbot
  - prediction (experimental, railgun/shotgun are hitscan so this almost does nothing heh)
  - prediction factor (as already mentioned...)
  - magnetic (tbd)

* esp
  - box
  - lines (to self)
  - health bar
  - headbox (which is a circle)
  - weapon

* misc
  - draw fov
  - debugging

uses bbox for estimated head position, true bone aimbot still needs to be done.<br/>
aim movement done by mouse, requiring ingame mouseinput-mode to be "Windows Input"<br/>
many resources are taken from [IoQuakeLive](https://github.com/skybersec/ioquakelive) <br/>

built with assistance from friendly AI locals and CE<br/>
powered by .NET 10<br/>
The project will be open-sourced upon completion.

video: [streamable](https://streamable.com/ohzlw3)
