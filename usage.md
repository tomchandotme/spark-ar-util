### Documentation

---

#### Installation

```javascript
import * as Utils from './utils.js'
```

---

#### Usage

1. randomNumber (lower, upper)

```javascript
// Random number from 0 to 10.
let rng = Utils.randomNumber(0,10)	// 3
```

2. randomElement (elements)

``` javascript
let array = ['Instagram','Facebook','Tinder','Linkedin']
// Random element from array
let pick = Utils.randomElement(array)	// 'Linkedin'
```

3. randomFloat (lower, upper)

``` javascript
// Random float number from 0.0 to 10.0
let rngFloat = Utils.randomFloat(0.0,10.0)	// 1.3394069566560396
```

4. randomNegativePositive (num)

``` javascript
// Random the sign of a number
let rngSign = Utils.randomNegativePositive(3.24)	// -3.24
```

5. log (str)

``` javascript
// Same as Diagnostics.log
Utils.log('Hello World!')
```

6. watch (str, signal)

``` javascript
// Same as Diagnostics.watch
Utils.watch('Left Eye Openness', leftEyeOpenness)
```

7. toggle (element, hide)

``` javascript
// Toggle the hidden attribute of a element
Utils.toggle(faceMask, true)
```

8. hide (element)

``` javascript
// Hide a element
Utils.hide(floatingText)
```

9. show (element)

``` javascript
// Show a element
Utils.hide(banner)
```

10.  showMultiple (elements)

```javascript
// Show all elements of an array
Utils.showMultiple(baseUI)
```

11.  hideMultiple (elements)

```javascript
// Hide all elements of an array
Utils.hideMultiple(baseUI)
```

12.  updateText (element, text)

``` javascript
// Update the text of a element
Utils.updateText(score, '00000')
```

13. tapRegistrar (element, fn)

``` javascript
// Registera function to tap gestures on a element
Utils.tapRegistrar(button, startGame)
```

14. getChildren (parent, childPrefix)

```javascript
// Get a set of duplicated elements as an array.
let planeChildren = Utils.getChildren (Scene,'plane')
```

15. checkCollisions (objects, colliderX, colliderY, onCollision)

``` javascript

```

16. countdown (from, to, time, everyTime, onComplete, triggerOnStart)

```javascript

```

17. swapMaterialTextureByName (matName, textureName)

```javascript

```

18. swapSceneObjectTexture (sceneObject, texture)

```javascript

```

19. randomTexture (textures, material)

``` javascript

```

20. randomizeTextures (objArray, textures)

``` javascript

```

21. tween (sampler, from, to, params, onComplete)

``` javascript

```

22. opacityTween (material, from, to, params, onComplete)

``` javascript

```

23. uvScroll (material, offsetU, offsetV, driverParameters, onComplete)

``` javascript

```

24. scaleTween (element, driverParams, sampler, from, to, axisArray, onComplete)

```  javascript

```

25. translateTween (element, driverParams, from, to, sampler, axisArray)

``` javascript

```

26. axisRotation (axis_x, axis_y, axis_z, angle_degrees)

``` javascript

```

27. rotateTween (element, driverParams, sampler, from, to, axisArray, onComplete)

``` javascript

```

28. bounce (element, duration, from, to)

``` javascript

```

29. padWithZeros (num, length)

```javascript
let score = 29365
let scoreString = Utils.padWithZeros(score, 9)	// '000029365'
```

30. throttle (fn, wait)

``` javascript

```

