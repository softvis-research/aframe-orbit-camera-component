# aframe-orbit-camera-component

This is a modified version of the [AFrame Orbict Controls Component](https://github.com/tizzle/aframe-orbit-controls-component). It allows users to rotate the camera around the center of the screen.

### API

| Property   | Description | Default Value |
| ---------- | ----------- | ------------- |
| enabled | Boolean – defines if the Orbit Controls are used | false
| target | String – the object the camera is looking at and orbits around | '' |
| enableRotate | Boolean – defines if the camera can be rotated | true |
| rotateSpeed | Number – rotation speed | 1 |
| enableZoom | Boolean – defines if the camera can be zoomed in or out | true |
| invertZoom | Boolean – defines if zooming is inverted | false |
| zoomSpeed | Number – zoom speed | 1 |
| enablePan | Boolean – defines if the camera can be panned (using the arrow keys) | true |
| panSpeed | Number – panning speed | 7 |
| enableDamping | Boolean – defines if the rotational movement of the camera is damped / eased | false |
| dampingFactor | Number – damping factor | 0.25 |
| minAzimuthAngle | Number – minimum azimuth angle – Defines how far you can orbit horizontally, lower limit | -Infinity |
| maxAzimuthAngle | Number – maximum azimuth angle – Defines how far you can orbit horizontally, upper limit | Infinity |
| minPolarAngle | Number – minimum polar angle – Defines how far you can orbit vertically, lower limit | 0 |
| maxPolarAngle | Number – maximum polar angle – Defines how far you can orbit vertically, upper limit | Math.PI |
| minZoom | Number – minimum zoom value – Defines how far you can zoom out for Orthographic Cameras | 0 |
| maxZoom | Number – maximum zoom value – Defines how far you can zoom in for Orthographic Cameras | Infinity |
| minDistance | Number – minimum distance – Defines how far you can zoom in for Perspective Cameras | 0 |
| maxDistance | Number – maximum distance – Defines how far you can zoom out for Perspective Cameras | Infinity |
| logPosition | Boolean – prints out camera position to console.log() when rotating | true |
