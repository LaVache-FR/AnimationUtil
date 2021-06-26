# AnimationUtil
Simple AnimationUtil using Easing functions. Can be used anywhere, Hacked-Client, Mods, etc..


Render example >
https://gyazo.com/780b5d84f7bc69f863acdcc7022591fe


Exemple example of how to use it.

```java

//Variable Initialization
Animate anim1 = new Animate();

//Set Easing Method
anim1.setEase(Easing.CUBIC_OUT);

//Set min Value
anim1.setMin(20);

//Set max Value
anim1.setMax(440);

//Set Animation Duration
anim1.setSpeed(200);

//Set Reversed Animation
anim1.setReversed(false);

//Update Animation
anim1.update();

drawRect(anim.getValue(), 10, 20, 20, 0xFFFFFFFF);
```
