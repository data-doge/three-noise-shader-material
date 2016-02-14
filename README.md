# three-noise-shader-material

@jeromeetienne's [threex.noiseshadermaterial](https://github.com/jeromeetienne/threex.noiseshadermaterial) repackaged as a node module

## install

`npm i --save three-noise-shader-material`

## usage

```js
var THREE = require('three')
var NoiseShaderMaterial = require('three-noise-shader-material')(THREE)

var geometry = new THREE.BoxGeometry(1, 1, 1)
var material = new NoiseShaderMaterial()
var cube = new THREE.Mesh(geometry, material)
```
