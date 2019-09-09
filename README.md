# This package is not maintained anymore. Feel free to copy the code  in your project. See the issue #1 for react-leaflet 2

# React Leaflet Rotated Marker

This is a react wrapper of [bbecquet's leaflet rotated marker](https://github.com/bbecquet/Leaflet.RotatedMarker) for [react-leaflet](https://github.com/PaulLeCam/react-leaflet).

Instead of extending react-leaflet's Marker, I created a new component named RotatedMarker.

## Installation

    yarn add react-leaflet-rotatedmarker

## Usage

```jsx
  import RotatedMarker from 'react-leaflet-rotatedmarker'

  <RotatedMarker position={position} rotationAngle={180} rotationOrigin={'center'} />
```
